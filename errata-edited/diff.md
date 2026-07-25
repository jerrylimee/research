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

32.

closed/open interval (≤ or < ?)
