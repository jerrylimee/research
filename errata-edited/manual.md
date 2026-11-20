# Manual

All the fixes in this document have been compared with ground truths and verified to be correct. For how I arrived at these fixes, please ask me in a future meeting. I remember all of them.

1. 3945 - must changed to should
2. 4016 - YYYYMMDDHHSSZ to YYYYMMDDHHMMSSZ (missing minutes originally)  
3. 4169 - I don't know how to fix this. Asked ChatGPT for fix [link](https://chatgpt.com/share/6ab82053-0288-83ea-8f74-25454bd94fc9)
4. 4197 - one or more to zero or more
5. 4212 - I don't know how to fix this. Asked ChatGPT for fix [link](https://chatgpt.com/share/6ab82053-0288-83ea-8f74-25454bd94fc9)
6. 4251 - deleted `[ "#" fragment ]`
7. 4252 - deleted `[ "#" fragment ]`
8. 4297 - `Length = 8` changed to `Length = 5` **INCORRECT** should be `Length = 4`. This means I don't know how to fix this.
9. 4380 - Googled "PBB I-SID List Sub-TLV type value" but still couldn't fix it.
10. 4408 - `recv R2,` changed to `recv R1,`
11. 4450 - deleted `"domain-name="` and `"domain-nmbr="`
12. 4503 - I don't know how to fix this. Asked ChatGPT for fix [link](https://chatgpt.com/share/6ab82053-0288-83ea-8f74-25454bd94fc9)
13. 4517 - `<sequence> </sequence>` changed to `<xsd:sequence> </xsd:sequence>`
14. 4667 - I don't know how to fix this. Asked ChatGPT for fix [link](https://chatgpt.com/share/6ab82053-0288-83ea-8f74-25454bd94fc9)
15. 4676 - I don't know how to fix this. Asked ChatGPT for fix [link](https://chatgpt.com/share/6ab82053-0288-83ea-8f74-25454bd94fc9)
16. 4724 - `For video on demand with content integrity protection enabled` changed to `For video on demand with or without content integrity protection enabled`
17. 4825 - I don't know how to fix this. Asked ChatGPT for fix [link](https://chatgpt.com/share/6ab82053-0288-83ea-8f74-25454bd94fc9)
18. 4839 - deleted `name or`
19. 4865 - `to 128.` changed to `to 96.`
20. 4874 - I don't know how to fix this. Asked ChatGPT for fix [link](https://chatgpt.com/share/6ab82053-0288-83ea-8f74-25454bd94fc9)
21. 4880 - `No integrity protection` changed to `Null` **INCORRECT** should be `Unassigned`
22. 4935 - I don't know how to fix this. Asked ChatGPT for fix [link](https://chatgpt.com/share/6ab82053-0288-83ea-8f74-25454bd94fc9)
23. 4949 - `4.02` changed to ``
24. 4980 - I don't know how to fix this. Asked ChatGPT for fix [link](https://chatgpt.com/share/6ab82053-0288-83ea-8f74-25454bd94fc9)
25. 5021 - `32` changed to `4` (Side note: the original errata is not 5021)
26. 5049 - I don't know how to fix this. Asked ChatGPT for fix [link](https://chatgpt.com/share/6ab82053-0288-83ea-8f74-25454bd94fc9)
27. 5053 - trivial
28. 5054 - trivial
29. 5055 - I don't know how to fix this. Asked ChatGPT for fix [link](https://chatgpt.com/share/6ab82053-0288-83ea-8f74-25454bd94fc9)
30. 5127 - I don't know how to fix this. Asked ChatGPT for fix [link](https://chatgpt.com/share/6ab82053-0288-83ea-8f74-25454bd94fc9)
31. 5128 - I don't know how to fix this. Asked ChatGPT for fix [link](https://claude.ai/share/60961684-06ab-4f1e-acca-7181b0d2e037)
32. 5131 - `the request MUST NOT be processed and a "404 Not Found" error response MUST be sent by the server` changed to `an <rpc-error> element is returned with an <error-tag> value of "data-missing"` **INCORRECT** should change from `"create"` to `"delete" or "move"`
33. 5150 - `"endpoint": ["acq1.ucdn.example"],` changed to 

```JSON
"endpoints": [
    "a.service123.ucdn.example",
    "b.service123.ucdn.example"
],
```
34. 
