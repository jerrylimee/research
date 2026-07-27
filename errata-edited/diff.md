# What was the problem and the fix? (In one sentence)

1. 3945 - differing levels of restriction (should vs must) (must was the right answer because of prior requirements) \
    **Fix:** looked at other text in the same section and adjusted wording
2. 4016 - the natural language description is right but the formal definition is wrong (missing minutes) \
    **Fix:** looked at the following natural language explanation and adjusted code
3. 4169 - example doesn't follow the description \
    **Fix:** looked at the formal definition and adjusted example
4. 4197 - off-by-one (inconsistent with existing text in the same section; 4.2) \
    **Fix:** looked at other text in the same section and adjusted natural language specification
5. 4212- ambiguous about what length is MAC'd and what length is encoded (on second thought are we sure that explanation is correct) (original text is wrong in its formal definition) \
    **Fix:** adjusted both formal and natural definition based on correspondence with implementers and addressed the ambiguity
6. 4251 - included something RFC 3986 does not allow (inconsistent with existing RFCs) \
    **Fix:** looked at other RFC's syntax requirement on URI scheme specifications (a concept related to the original text) and adjusted definition
7. 4252 - same as 4251 \
    **Fix:** same as 4251
8. 4297 - violated RFC 4379 section 3 \
    **Fix:** looked at other RFC's requirement on the length value in LSP Ping TTL (again, a concept related to the original text) and adjusted definition
9. 4380 - typo migrated from some other drafts \
    **Fix:** looked at other text in the same section and adjusted type values
10. 4408 - diagram not consistent with Section 6.8 of the same RFC's specification \
    **Fix:** looked at other section in the same document for relevant specification (relevant to concept of state transition) and adjusted diagram
11. 4450 - description doesn't follow the example \
    **Fix:** looked at the example and adjusted formal definition
12. 4503 - example not consistent with RFC 5890 (inconsistent with existing RFCs) \
    **Fix:** looked at other RFC's syntax requirement on unicodeName (a concept related to the original text) and adjusted example
13. 4517 - **there is no way of fixing this without knowledge on what tags are used in actual schemas**
14. 4667 - **there is no way of fixing this without knowledge on what the common practice on whitespace is**
15. 4676 - **there is no way of fixing this without knowledge on what the boundary hyphens do to a message**
16. 4724 - description not consistent with Section 5 and 6.1 of the same RFC's specification \
    **Fix:** looked at those sections to see their specification on content integrity protection scheme
17. 4825 - same as 4667 \
    **Fix:** same as 4667
18. 4839 - description not consistent with ABNF rules **there is no way of fixing this without knowledge on what the ABNF rules are**
19. 4865 - description not consistent with Section 5.1 of RFC 7599's specification on DMR IPv6 prefix length \
    **Fix:** looked at other RFC's requirement on DMR IPv6 prefix length and adjusted description
20. 4874 - formal definition contains a logical error \
    **Fix:** follow the code line-by-line and see what is implausible
21. 4880 - description not consistent with prior sentences in the same section of the same RFC's specification \
    **Fix:** looked at the context to see their specification on content integrity protection method
22. 4935 - examples are invalid **there is no way of fixing this without knowledge on what parsable RRSIG records need to look like**
23. 4949 - handling of unsupported reserved option numbers in responses is invalid **there is no way of fixing this without knowing how to handle this specific type of response**
24. 4980 - description not consistent with Section 3 of the same RFC's specification \
    **Fix:** looked at those sections to see their specification on country code
25. 5021 - definition inconsistent with other RFC (RFC 7787 says bytes but this one says bits) \
    **Fix:** looked at other RFC's requirement on DNCP_NODE_IDENTIFIER_LENGTH and adjusted definition
26. 5049 - definition inconsistent with other RFC \
    **Fix:** looked at other RFC's requirement on CDNSKEY and CDS records and adjusted definition
27. 5053 - American vs British English
28. 5054 - American vs British English
29. 5055 - formal definition inconsistent with other RFC \
    **Fix:** looked at other RFC's requirement on response code with any human-readable text suffix and adjusted definition
30. 5127 - formal definition inconsistent with other RFC (RFC 5246) \
    **Fix:** looked at other RFC's requirement on response code with any human-readable text suffix and adjusted definition
31. 5128 - same as 5127
32. 5131 - description not consistent with Section 2.2 of the same RFC's specification \
    **Fix:** looked at those sections to see their specification on the requirement of semantics mirroring Section 7.2 of RFC6241
33. 5150 - property name not consistent with type of value it receives \
    **Fix:** corrected property name to plural form \
    **OR:** looked at examples in Section 4.2.1.1 of the same RFC to see how they handled the property names
34. 5255 - description doesn't follow the example \
    **Fix:** looked at the example and adjusted formal definition
35. 5274 - prefix missing in namespace declaration tags **there is no way of fixing this without knowledge on what XML instances need prefixes**
36. 5324 - incorrect PSID value **there is no way of fixing this without knowledge on what PSID values are correct for IPv4, IPv6 and port ranges presented in the example**
37. 5342 - definition inconsistent with text from the same section Section 4.11 \
    **Fix:** looked at the context to see their specification on how to set the KeepaliveTimer
38. 5351 - inconsistent with Section 2.5.2 \
    **Fix:** looked at that section to see their specification on their handling of multiple bytes types with HEXBIN and adjusted definition
39. 5353 - error in calculation \
    **Fix:** calculated what the correct number would be
40. 5374 - country tag inconsistent with IANA \
    **Fix:** looked at IANA language subtag registry
41. 5387 - country tag inconsistent with IANA \
    **Fix:** looked at IANA language subtag registry
42. 5402 - specification not corresponding to the diagram (typo) \
    **Fix:** looked at diagram
43. 5543 - inconsistent with Section 3.12.5 \
    **Fix:** looked at Section 3.12.5 for the original schema definition for the Confidence element
44. 5544 - inconsistent with Section 3.18 \
    **Fix:** looked at Section 3.18 for the requirement on DomainData and Address and adjusted formal code
45. 5545 - terminology inconsistent with IANA \
    **Fix:** looked at IANA language registry
46. 5566 - inconsistent with Section 6.1 of RFC 7591 \
    **Fix:** looked at other RFC's requirement on "gap" leaf and adjusted definition
47. 5622 - incorrect calculation of maximum message length \
    **Fix:** recalculated, but **there is no way of fixing this without knowledge on how long the message length field is, which is explained in original RFC but not in original text**
48. 5715 - terminology inconsistent with RFC 8225 and the provided example; one used "array", one used "object" (it's an object containing an array, not simply an array) \
    **Fix:** find and replace almost all occurrences of array to object; looked at other RFC's requirement on "dest" element and adjusted definition
49. 5729 - inconsistent with Section 8 \
    **Fix:** looked at Section 8 for the requirement on JWS-signed response objects and adjusted natural language definition
50. 5732 - logically prevents the process outlined in Section 8.2 of the same RFC from ever happening \
    **Fix:** looked at Section 8.2 for the requirement on the retry mechanism and adjusted natural language definition
51. 5765 - inconsistent with Section 4.3.1 \
    **Fix:** looked at Section 8 for the requirement on all outer TLVs and adjusted definition
52. 5791 - wrong property name and missing comma \
    **Fix:** needs to go through the code line-by-line to see what's wrong
53. 5844 - example in C.1 not consistent with Section 3.3.2 \
    **Fix:** looked at Section 3.3.2 for the requirement on Intermediate-Result TLV and adjusted example
54. 5877 - example uses wrong match type **there is no way of fixing this without knowledge on what the correct match type should be to extract a match variable**
55. 5970 - inconsistent with RFC 8231 Section 6.3 \
    **Fix:** looked at other RFC's requirement on LSP Object and adjusted definition
56. 5983 - inconsistent with other examples in same RFC \
    **Fix:** looked at those other examples and compared differences
57. 5986 - value for count prevents code from running correctly \
    **Fix:** run it line-by-line and see what's wrong
58. 5996 - **there is no way of fixing this without knowledge on what the error condition in COBS encoding is**
59. 6078 - inconsistent with Section 9.3.4 \
    **Fix:** looked at Section 9.3.4 for the requirement on valid decimal64 value with 18 fraction digits and adjusted example
60. 6178 - example inconsistent with naming guidelines specified in Section 4 \
    **Fix:** looked at Section 4 for the requirement on member name naming guidelines and adjusted example
61. 6218 - trailing root label of domain name missing **there is no way of fixing this without knowing traling root label is required**
62. 6231 - **there is no way of fixing this without knowing that LSP Object is not part of the PCErr message**
63. 6258 - inconsistent with rules in Section 7.1.5 \
    **Fix:** looked at Section 7.1.5 for the requirement of the mandatory "prefix" substatement and adjusted example
64. 6268 - formal code description inconsistent with rules in Section 5. STUN Message Structure \
    **Fix:** looked at Section 5 for STUN Message Structure and adjusted code
65. 6289 - wrong subject **there is no way of fixing this without being capable of figuring out what the author's original intent was or knowing what the value portion of the TLV in octets looks like**
66. 6295 - typo
67. 6364 - definition does not correspond to the example \
    **Fix:** looked at example and **extended** definition to accommodate the example's case (rare because typically the definition is simply modified)
68. 6435 - definition not consistent with RFC 8259 Section 11 \
    **Fix:** looked at other RFC's requirement on charset parameter on application/json and adjusted definition
69. 6473 - example not consistent with RFC 7591 \
    **Fix:** looked at other RFC's requirement on lists in the YANG model and adjusted example
70. 6499 - definition not consistent with RFC 8225 \
    **Fix:** looked at other RFC's requirement on encoding signed-identity-digest and adjusted definition
71. 6609 - figure logically ill **there is no way of fixing this without knowing how TCP Fastopen with MPTCPv1 works**
72. 6646 - **there is no way of fixing this without knowing how boolean values are represented in JSON**
73. 6656 - code definition inconsistent with RFC8225 Section 5.1.1 \
    **Fix:** looked at other RFC's requirement on 'iat' being a NumericDate format and adjusted definition
74. 6684 - contradict text in same section \
    **Fix:** looked at the context to see their specification on OPTION_V4_SZTP_REDIRECT in DHCP messages adjusted definition
75. 6753 - contradict text in same section \
    **Fix:** looked at the context to see their specification on when does the NT field have no meaning and adjusted definition
76. 6842 - **there is no way of fixing this without knowing what the tx-frequency for the two CTs under XPIC configuration should be**
77. 6849 - example inconsistent with specification \
    **Fix:** looked at the RFC document to see what should "main" be replaced with
78. 6900 - **there is no way of fixing this without knowing what the definition of the network-id type as an IETF URI is**
79. 6922 - **there is no way of fixing this without knowing that the cos-id must be included when the bandwidth type is set to "bw-per-cos"**
80. 6940 - **there is no way of fixing this without knowing that the `field must be empty` part is ambiguous**
81. 7014 - description of ":path" field inconsistent with existing RFCs (RFC 9110, 9112, 9113) \
      **Fix:** looked at other RFC's requirement on ":path" header field and adjusted definition
82. 7016 - length and size of Operator-Identifier is not compatible **there is no way of fixing this without knowing what a length of 4 means for Operator-Identifier**
83. 7094 - string identifier incomplete / inconsistent with example in Section 4.1 of same RFC document \
    **Fix:** looked at Section 4.1 for their string identifier and adjusted description
84. 7118 - definition interval inconsistent with Section 7 \
    **Fix:** looked at Section 7 for CA's manifest and adjusted description
85. 7132 - rid-id in code definition inconsistent with RFC 8852's restriction to only alphanumeric characters \
    **Fix:** looked at other RFC's requirement of only alphanumeric characters in rid-id and adjusted code
86. 7134 - EVPN Route Type 4 not imported correctly from RFC 7432 Section 7.4 \
    **Fix:** looked at other RFC's Ethernet Segment Route format and adjusted diagram
87. 7138 - quality value for the media type "text/html;level=3" incorrect **there is no way of fixing this without knowing how quality value should be calculated**
88. 7145 - text contradict its following text \
    **Fix:** added "except as noted below" to address logical loophole
89. 7148 - handling an INIT ACK chunk with a_rwnd less than 1500 inconsistent with handling of other error conditions **there is no way of fixing this without knowing the handling of OS = 0 or MIS = 0**
90. 7173 - subdomain of figure does not correspond to the one in the text \
    **Fix:** looked at figure and adjusted text
91. 7306 - ABNF missing optional whitespace (OWS) \
    **Fix:** code definition inconsistent with example; looked at example and adjusted code to accommodate
92. 7323 - BADCHARSET response code missing parentheses **there is no way of fixing this without knowing the server should consider a wider range of cases**
93. 7381 - code definition inconsistent with RFC 9074's examples \
    **Fix:** looked at other RFC's list of allowed properties in the "locprop" definition and adjusted code definition
94. 7386 - violates Section 18.50.3 of same RFC document \
    **Fix:** looked at Section 18.50.3 for what the first operation in a COMPOUND can be and adjusted description
95. 7387 - uses wrong timer **there is no way of fixing this without knowing what timer a packet containing an COOKIE-ECHO chunk uses**
96. 7389 - wrongly claims Uri-Path option is mandatory **field knowledge required**
97. 7400 - stylistic issues; inconsistent with RFC 9112's HTTP-message definition \
    **Fix:** looked at other RFC's HTTP-message definition and adjusted code definition
98. 7539 - code definition inconsistent with Section 2 of the referred RFC 6298 \
    **Fix:** looked at other RFC's order of computing rttvar and smoothed_rtt and adjusted code definition
99. 7565 - definition incorrect in its treatment of prepended zero octets in the fields of a JWK object **there is no way of fixing this without knowing in what fields should prepended zero octets be stripped**
100. 7571 - table contains typo **field knowledge and context required**
101. 7639 - terminology inconsistent with the IANA "Reply Modes" sub-registry \
    **Fix:** looked at the IANA "Reply Modes" sub-registry and adjusted use of term
102. 7657 - hierarchical error and JSON data type mismatch \
    **Fix:** go through code definition line-by-line
103. 7679 - JSON data type mismatch \
    **Fix:** go through code definition line-by-line; **also need to know that purpose is of token type instead of string type**
104. 7799 - table inconsistent with Table 1 of Section 6.1.1 of FIPS 186-5, and Section 9 Paragraph 5 of RFC 5656 \
    **Fix:** looked at other RFC's description on the security length of P-521 and adjusted table
105. 7817 - closed/open interval (≥ or > ?) \
    **Fix**: looked at example below the original text in the next paragraph and adjusted description
106. 7833 - definition inconsistent with RFC 5652 Section 6.1 \
    **Fix:** looked at other RFC's description on the version number when using PasswordRecipientInfo and adjusted specification
107. 7876 - code definition inconsistent with the requirement in RFC 9083 \
    **Fix:** looked at other RFC's requirement that URIs must be different to prevent infinite client processing loops and adjusted code definition
108. 7883 - differing levels of restriction (should vs must); inconsistent with Section 7.5 of that same RFC \
    **Fix:** looked at other section in the same RFC and adjusted wording
109. 7929 - code description inconsistent with Figure 30 \
    **Fix:** looked at figure and adjusted code description
110. 7958 - **there is no way of fixing this without knowing what the first row of the table is matching**
111. 7986 - example inconsistent with Section 4.1 of the same RFC \
    **Fix:** looked at Section 4.1 for the required "rdapConformance" property and adjusted example
112. 7997 - the record type used for DS record calculation is incorrect **there is no way of fixing this without knowing what the record type used for DS record calculation is**
113. 8020 - example inconsistent with its text description in Section 6.2 \
    **Fix:** looked at Section 6.2 for IPFIX option-template and adjusted example
114. 8105 - example violates the ABNF rules specified in Sections 2.1 and 2.2 \
    **Fix:** looked at Sections 2.1 and 2.2 for restrictions on backslashes nor parentheses in the ABNF rules and adjusted example
115. 8131 - example inconsistent with RFC 8407bis \
    **Fix:** looked at RFC 8407bis guidelines for properly qualified URIs and adjusted example
116. 8132 - same as 8131
117. 8133 - same as 8131
118. 8134 - same as 8131
119. 8256 - diagram contradicts textual description \
    **Fix:** corrected diagram label by looking at textual description
120. 3944 - typo; **there is no way of fixing this without knowing that ODU is wrong and ODTU is the correct term**
121. 3946 - wrong message type **there is no way of fixing this without knowing what is the usual mechanism to teardown old control state**
122. 4132 - wrong indentation **there is no way of fixing this without knowing what is the correct indentation**
123. 4471 - definition of LOCK4denied response inconsistent with Section 16.11.4 \
    **Fix:** looked at Section 16.11.4 for the lock type information and adjusted definition
124. 4549 - wrong type of AVP used **there is no way of fixing this without knowing what is the correct AVP to be used**
125. 4664 - wrong term **there is no way of fixing this without knowing how the overlap occurs**
126. 4673 - **there is no way of fixing this without knowing that pcePcepSessDown requires IDLE state**
127. 5066 - **there is no way of fixing this without knowing the set of structure that need to be canonically encoded**
128. 5078 - **there is no way of fixing this without guessing the author's intent and how Content-Format code attribute appears in a link**
129. 5225 - **there is no way of fixing this without knowing that for MAP-T the complete IPv4 source address must be embedded in the interface-identifier for correct translation in the case of an IPv4 prefix**
130. 5376 - wrong message type **there is no way of fixing this without knowing what message type PCC needs to issue**
131. 5395 - incorrect reference \
    **Fix:** looked at context to see which RFC contains information on DNS records that would be classified "indeterminate"
132. 5474 - closed/open interval (≥ or > ?) \
    **Fix**: looked at context to see what the ranges do not overlap with the selected representation
133. 5483 - definition inconsistent with Section 7.4.2 of the same RFC and RFC 7748 \
    **Fix:** looked at Section 18.50.3 and other RFC's on description of byte string inputs to the corresponding ECDH scalar multiplication function and adjusted definition
134. 5489 - wrong substatement type **there is no way of fixing this without knowing what is the correct statement that contains substatements that identify properties to delete**
135. 5615 - wrong type of header **field expertise required**
136. 5650 - quotes wrong COSE registry \
    **Fix:** looked at COSE registries that actually contain the set of curve identifiers
137. 5664 - wrong terms **field expertise required**
138. 5669 - wrong terms \
    **Fix:** looked at context to see what the registry in this section is about (not curves but key types)
139. 5687 - wrong terms \
    **Fix:** looked at context to see what is the parameter sent in the authorization/token request
140. 5703 - incorrect reference (referenced the wrong section) \
    **Fix:** looked at RFC8017 to see which section contains relevant information
141. 5756 - wrong name used in YANG module \
    **Fix:** looked at section and located which RFC contains a concept with a name similar to "system-restart" and searched for the actual name of the concept which is "system-reset"
142. 5845 - inconsistent with multiple other sections of the same RFC \
    **Fix:** looked at instances of "upon method completion" in other sections to see how they handled it and adjusted natural language definition
143. 