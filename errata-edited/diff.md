# What was the problem and the fix? (In one sentence)

1. 3945 - differing levels of restriction (should vs must) (must was the right answer because of prior requirements)

    **Fix:** looked at other text in the same section and adjusted wording

2. 4016 - the natural language description is right but the formal definition is wrong (missing minutes)

    **Fix:** looked at the following natural language explanation and adjusted code

3. 4169 - example doesn't follow the description

    **Fix:** looked at the formal definition and adjusted example

4. 4197 - off-by-one (inconsistent with existing text in the same section; 4.2)

    **Fix:** looked at other text in the same section and adjusted natural language specification

5. 4212- ambiguous about what length is MAC'd and what length is encoded (on second thought are we sure that explanation is correct) (original text is wrong in its formal definition)

    **Fix:** adjusted both formal and natural definition based on correspondence with implementers and addressed the ambiguity

6. 4251 - included something RFC 3986 does not allow (inconsistent with existing RFCs)

    **Fix:** looked at other RFC's syntax requirement on URI scheme specifications (a concept related to the original text) and adjusted definition

7. 4252 - same as 4251

    **Fix:** same as 4251

8. 4297 - violated RFC 4379 section 3

    **Fix:** looked at other RFC's requirement on the length value in LSP Ping TTL (again, a concept related to the original text) and adjusted definition

9. 4380 - typo migrated from some other drafts

    **Fix:** looked at other text in the same section and adjusted type values

10. 4408 - diagram not consistent with Section 6.8 of the same RFC's specification

    **Fix:** looked at other section in the same document for relevant specification (relevant to concept of state transition) and adjusted diagram

11. 4450 - description doesn't follow the example

    **Fix:** looked at the example and adjusted formal definition

12. 4503 - example not consistent with RFC 5890 (inconsistent with existing RFCs)

    **Fix:** looked at other RFC's syntax requirement on unicodeName (a concept related to the original text) and adjusted example

13. 4517 - **there is no way of fixing this without knowledge on what tags are used in actual schemas**

14. 4667 - **there is no way of fixing this without knowledge on what the common practice on whitespace is**

15. 4676 - **there is no way of fixing this without knowledge on what the boundary hyphens do to a message**

16. 4724 - description not consistent with Section 5 and 6.1 of the same RFC's specification

    **Fix:** looked at those sections to see their specification on content integrity protection scheme

17. 4825 - same as 4667

    **Fix:** same as 4667

18. 4839 - description not consistent with ABNF rules **there is no way of fixing this without knowledge on what the ABNF rules are**

19. 4865 - description not consistent with Section 5.1 of RFC 7599's specification on DMR IPv6 prefix length

    **Fix:** looked at other RFC's requirement on DMR IPv6 prefix length and adjusted description

20. 4874 - formal definition contains a logical error

    **Fix:** follow the code line-by-line and see what is implausible

21. 4880 - description not consistent with prior sentences in the same section of the same RFC's specification

    **Fix:** looked at the context to see their specification on content integrity protection method

22. 4935 - examples are invalid **there is no way of fixing this without knowledge on what parsable RRSIG records need to look like**

23. 4949 - handling of unsupported reserved option numbers in responses is invalid **there is no way of fixing this without knowing how to handle this specific type of response**

24. 4980 - description not consistent with Section 3 of the same RFC's specification

    **Fix:** looked at those sections to see their specification on country code

25. 5021 - definition inconsistent with other RFC (RFC 7787 says bytes but this one says bits)

    **Fix:** looked at other RFC's requirement on DNCP_NODE_IDENTIFIER_LENGTH and adjusted definition

26. 5049 - definition inconsistent with other RFC

    **Fix:** looked at other RFC's requirement on CDNSKEY and CDS records and adjusted definition

27. 5053 - American vs British English

28. 5054 - American vs British English

29. 5055 - formal definition inconsistent with other RFC

    **Fix:** looked at other RFC's requirement on response code with any human-readable text suffix and adjusted definition

30. 5127 - formal definition inconsistent with other RFC (RFC 5246)

    **Fix:** looked at other RFC's requirement on response code with any human-readable text suffix and adjusted definition

31. 5128 - same as 5127

32. 5131 - description not consistent with Section 2.2 of the same RFC's specification

    **Fix:** looked at those sections to see their specification on the requirement of semantics mirroring Section 7.2 of RFC6241

33. 5150 - property name not consistent with type of value it receives

    **Fix:** corrected property name to plural form
    **OR:** looked at examples in Section 4.2.1.1 of the same RFC to see how they handled the property names

34. 5255 - description doesn't follow the example

    **Fix:** looked at the example and adjusted formal definition

35. 5274 - prefix missing in namespace declaration tags **there is no way of fixing this without knowledge on what XML instances need prefixes**

36. 5324 - incorrect PSID value **there is no way of fixing this without knowledge on what PSID values are correct for IPv4, IPv6 and port ranges presented in the example**

37. 5342 - definition inconsistent with text from the same section Section 4.11

    **Fix:** looked at the context to see their specification on how to set the KeepaliveTimer

38. 5351 - inconsistent with Section 2.5.2

    **Fix:** looked at that section to see their specification on their handling of multiple bytes types with HEXBIN and adjusted definition

39. 5353 - error in calculation

    **Fix:** calculated what the correct number would be

40. 5374 - country tag inconsistent with IANA

    **Fix:** looked at IANA language subtag registry

41. 5387 - country tag inconsistent with IANA

    **Fix:** looked at IANA language subtag registry

42. 5402 - specification not corresponding to the diagram (typo)

    **Fix:** looked at diagram

43. 5543 - inconsistent with Section 3.12.5

    **Fix:** looked at Section 3.12.5 for the original schema definition for the Confidence element

44. 5544 - inconsistent with Section 3.18

    **Fix:** looked at Section 3.18 for the requirement on DomainData and Address and adjusted formal code

45. 5545 - terminology inconsistent with IANA

    **Fix:** looked at IANA language registry

46. 5566 - inconsistent with Section 6.1 of RFC 7591

    **Fix:** looked at other RFC's requirement on "gap" leaf and adjusted definition

47. 5622 - incorrect calculation of maximum message length

    **Fix:** recalculated, but  **there is no way of fixing this without knowledge on how long the message length field is, which is explained in original RFC but not in original text**

48. 5715 - terminology inconsistent with RFC 8225 and the provided example; one used "array", one used "object" (it's an object containing an array, not simply an array)

    **Fix:** find and replace almost all occurrences of array to object; looked at other RFC's requirement on "dest" element and adjusted definition

49. 5729 - inconsistent with Section 8

    **Fix:** looked at Section 8 for the requirement on JWS-signed response objects and adjusted natural language definition

50. 5732 - logically prevents the process outlined in Section 8.2 of the same RFC from ever happening

    **Fix:** looked at Section 8.2 for the requirement on the retry mechanism and adjusted natural language definition

51. 5765 - inconsistent with Section 4.3.1

    **Fix:** looked at Section 8 for the requirement on all outer TLVs and adjusted definition

52. 5791 - wrong property name and missing comma

    **Fix:** needs to go through the code line-by-line to see what's wrong

53. 5844 - example in C.1 not consistent with Section 3.3.2

    **Fix:** looked at Section 3.3.2 for the requirement on Intermediate-Result TLV and adjusted example

54. 5877 - example uses wrong match type **there is no way of fixing this without knowledge on what the correct match type should be to extract a match variable**

55. 5970 - inconsistent with RFC 8231 Section 6.3

    **Fix:** looked at other RFC's requirement on LSP Object and adjusted definition

56. 5983 - inconsistent with other examples in same RFC

    **Fix:** looked at those other examples and compared differences

57. 5986 - value for count prevents code from running correctly

    **Fix:** run it line-by-line and see what's wrong

58. 5996 - **there is no way of fixing this without knowledge on what the error condition in COBS encoding is**

59. 6078 - inconsistent with Section 9.3.4

    **Fix:** looked at Section 9.3.4 for the requirement on valid decimal64 value with 18 fraction digits and adjusted example

60. 6178 - example inconsistent with naming guidelines specified in Section 4

    **Fix:** looked at Section 4 for the requirement on member name naming guidelines and adjusted example

61. 6218 - trailing root label of domain name missing **there is no way of fixing this without knowing traling root label is required**

62. 6231 - **there is no way of fixing this without knowing that LSP Object is not part of the PCErr message**

63. 6258 - inconsistent with rules in Section 7.1.5

    **Fix:** looked at Section 7.1.5 for the requirement of the mandatory "prefix" substatement and adjusted example

64. 6268 - formal code description inconsistent with rules in Section 5. STUN Message Structure

    **Fix:** looked at Section 5 for STUN Message Structure and adjusted code

65. 6289 - wrong subject **there is no way of fixing this without being capable of figuring out what the author's original intent was or knowing what the value portion of the TLV in octets looks like**

66. 6295 - typo

67. 6364 - definition does not correspond to the example

    **Fix:** looked at example and **extended** definition to accommodate the example's case (rare because typically the definition is simply modified)

68. 6435 - definition not consistent with RFC 8259 Section 11

    **Fix:** looked at other RFC's requirement on charset parameter on application/json and adjusted definition

69. 6473 - example not consistent with RFC 7591

    **Fix:** looked at other RFC's requirement on lists in the YANG model and adjusted example

70. 6499 - definition not consistent with RFC 8225

    **Fix:** looked at other RFC's requirement on encoding signed-identity-digest and adjusted definition

71. 6609 - figure logically ill **there is no way of fixing this without knowing how TCP Fastopen with MPTCPv1 works**

72. 6646 - **there is no way of fixing this without knowing how boolean values are represented in JSON**

73. 6656 - code definition inconsistent with RFC8225 Section 5.1.1

    **Fix:** looked at other RFC's requirement on 'iat' being a NumericDate format and adjusted definition

74. 

closed/open interval (≤ or < ?)
