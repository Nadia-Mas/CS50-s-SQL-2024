# CS50-s-SQL-2024

In this repository, I solve all the dquestion in the course of CS50's sql 2024. ALso, I added the ERD for questions. I hope you enjoy it.

![logo (1)](https://github.com/Nadia-Mas/CS50-s-SQL-2024/assets/88572957/c07d7344-1b76-458b-a962-1f88a89b6b8f)<?xml version="1.0" encoding="UTF-8"?><svg id="Layer_2" xmlns="http://www.w3.org/2000/svg" width="798.2248" height="200" viewBox="0 0 798.2248 200"><g id="Layer_1-2"><g><g><path d="M322.3185,136.5641c0-1.6875-1.0996-2.9359-3.3478-3.4225v-1.0914c1.2445,0,5.3897,.1666,6.5557,.1666,1.008,0,5.0218-.1666,6.2707-.1666v1.0914c-2.0859,.407-3.1817,1.639-3.1817,3.4225v21.42c0,6.783,3.7249,10.6174,11.5164,10.6174,6.7132,0,11.9366-3.0144,11.9366-10.1134v-22.0074c0-1.5905-.9989-2.8526-3.5146-3.3391v-1.0914c.9159,0,4.3428,.1666,5.5127,.1666,.9993,0,4.5967-.1666,5.5171-.1666v1.0914c-2.4275,.5786-3.5059,1.6652-3.5059,3.3391v20.8278c0,9.3477-5.4381,14.7155-17.1731,14.7155-10.9247,0-16.5863-4.9657-16.5863-13.7472v-21.7127Z" fill="#fff"/><path d="M369.1805,170.3453c2.5415-.473,3.5451-1.7612,3.5451-3.3392v-29.6055c0-2.5104-1.3366-3.6406-3.6154-4.2628v-1.0914c1.2886,.0959,3.453,.1531,4.5575,.1531,1.0037,0,2.5632-.0175,3.6149-.1531l25.679,30.1929v-25.7585c0-1.5867-1.0081-2.8487-3.5137-3.343v-1.0914c.9199,0,4.2241,.1705,5.3979,.1705,1.0216,0,4.5624-.1705,5.4948-.1705v1.0914c-2.4493,.5777-3.6318,1.6739-3.6318,3.343v35.5433h-1.547c-.9732-.2239-2.8138-1.2707-5.618-4.3472l-22.9751-26.7617v26.0909c0,1.5867,.9154,2.8438,3.422,3.3392v1.0963c-.9199,0-4.2241-.1755-5.3984-.1755-1.0124,0-4.4785,.1755-5.4119,.1755v-1.0963Z" fill="#fff"/><path d="M571.8073,162.3613h1.0865c.5748,2.2129,1.8407,4.229,3.6154,5.394,1.8455,1.3017,4.7416,1.924,7.0815,1.924,5.1662,0,8.4404-2.559,8.4404-6.6085,0-4.1931-4.1941-6.3711-9.2198-8.8825-3.7385-1.8706-11.0827-4.9597-11.0827-12.0587,0-6.6134,5.0441-10.7279,13.1114-10.7279,5.3242,0,7.822,1.3018,11.4151,1.1351l-.0698,8.0237h-1.0963c-1.4374-4.7281-5.7313-6.3759-10.4332-6.3759-5.2583,0-7.226,3.0066-7.226,6.0647,0,4.3782,4.2852,6.5862,9.1403,8.7516,5.4609,2.4319,11.3851,5.5035,11.3851,12.3437,0,6.4767-5.0654,11.166-14.3249,11.166-5.5084,0-8.8126-1.5732-11.7089-1.9289l-.1143-8.2204Z" fill="#fff"/><path d="M688.1473,153.5274v13.4002c0,1.3279,1.012,2.997,3.2995,3.4177v1.0963c-1.2746,0-5.4377-.1755-6.6425-.1755-1.0129,0-5.0054,.1755-6.4466,.1755v-1.0963c2.2961-.4207,3.3963-2.0898,3.3963-3.4177v-12.8129m.4071,1.0294l-10.4556-16.7743c-1.7835-2.9446-3.1501-4.4964-5.14-5.2321v-1.0875c1.4335,0,5.3029,.1715,6.4021,.1715,.9944,0,5.1711-.1715,6.6783-.1715v1.0875c-1.3366,.2364-1.9627,.9062-1.9627,1.9143,0,.8898,.6048,2.0335,1.2135,3.028,.5961,.9857,7.7086,12.7828,7.7086,12.7828l7.4267-12.778c.7502-1.2794,1.2804-2.5501,1.2804-3.3875,0-.7629-.5399-1.3938-1.8057-1.5596v-1.0875c1.258,0,3.9003,.1715,4.7416,.1715s3.878-.1715,5.1265-.1715v1.0129c-2.8564,1.1699-4.6399,3.6765-6.371,6.5813l-9.5047,15.8854" fill="#fff"/><path d="M487.8818,132.0503h24.5177c.758,0,2.0859-.0872,2.8438-.4159h1.0963l-.1715,7.9665h-1.0865c-.9335-2.5066-1.9018-4.514-6.6473-4.514h-10.6446v13.8829h8.2039c1.1961,0,2.6461-.1007,3.2733-.25,1.8445-.4033,2.6557-1.4288,3.0279-3.0018h1.0954c-.0786,1.2009-.0786,3.9401-.0786,4.7504,0,.8152,.0786,3.6988,.0786,5.0044h-1.0954c-.5262-1.5693-1.2445-2.7605-3.0279-3.1986-.6272-.1666-2.1034-.3024-3.2733-.3024h-8.2039v16.2839h11.5779c5.0567,0,6.5251-2.1081,7.7823-5.0877l1.0828,.254-1.0828,8.1816c-3.7597-.3334-6.0163-.3334-10.2849-.3334h-12.2341c-1.1786,0-5.5045,.1716-6.7617,.1716v-1.0914c2.208-.4207,3.4971-1.5121,3.4971-3.629v-30.1172c0-1.8669-1.0041-3.0329-3.4845-3.4488v-1.1049Z" fill="#fff"/><path d="M425.2617,136.8181c0-2.02-1.2047-3.1327-3.5669-3.6416v-1.0817c1.3153,0,5.5704,.1658,6.8101,.1658,1.0391,0,5.4124-.1658,6.7442-.1658v1.0817c-2.3485,.5089-3.5805,1.516-3.5805,3.6416v29.9079c0,2.0199,1.2097,3.12,3.5805,3.6193v1.0963c-1.3279,0-5.5219-.1716-6.7442-.1716-1.0565,0-5.4948,.1716-6.814,.1716v-1.0963c2.4144-.4507,3.5707-1.5073,3.5707-3.6193v-29.9079Z" fill="#fff"/><path d="M611.2509,136.8181c0-2.02-1.2183-3.1327-3.5756-3.6416v-1.0817c1.3143,0,5.5733,.1658,6.8043,.1658,1.0477,0,5.4211-.1658,6.7491-.1658v1.0817c-2.3485,.5089-3.5757,1.516-3.5757,3.6416v29.9079c0,2.0199,1.2097,3.12,3.5757,3.6193v1.0963c-1.3192,0-5.5084-.1716-6.7491-.1716-1.0381,0-5.49,.1716-6.8043,.1716v-1.0963c2.4096-.4507,3.5756-1.5073,3.5756-3.6193v-29.9079Z" fill="#fff"/><path d="M645.3296,132.2169c-13.4399,0-15.5908-.25-18.3387-.4206l.0223,8.1158h1.0953c1.0032-3.5979,3.0057-4.4345,5.6005-4.4345h8.4307v31.2484c0,2.112-1.1563,3.1686-3.5756,3.6193v1.0963c1.3279,0,5.8059-.1716,6.8402-.1716,1.2319,0,5.4386,.1716,6.7491,.1716v-1.0963c-2.3757-.4992-3.5805-1.5994-3.5805-3.6193v-31.2484h8.3648c2.6907,0,4.6147,.9159,5.618,4.4345h1.0827l.0175-8.1158c-2.7305,.1706-4.8813,.4206-18.3261,.4206" fill="#fff"/><path d="M538.0834,150.6699c1.2533,.1706,3.0978,.2501,4.921,.2501,7.3751,0,9.6976-4.2425,9.6976-7.9975,0-5.3107-3.5456-8.6023-10-8.6023-1.3366,0-3.2733,.1666-4.6186,.4206v15.929Zm0,16.0561c0,2.0199,1.2833,3.1153,3.6541,3.6193v1.0963c-1.3143,0-5.6131-.1716-6.8402-.1716-1.0517,0-5.2496,.1716-6.5727,.1716v-1.0963c2.1993-.4207,3.4962-1.5073,3.4962-3.6193v-30.2142c0-1.8581-1.0119-3.028-3.4875-3.4487v-1.0866c1.3143,0,5.4725,.1658,6.6473,.1658,1.924,0,7.3926-.3237,9.5444-.3237,9.4214,0,14.6661,3.8955,14.6661,10.5738,0,5.2495-3.9042,8.799-9.9167,10.2491,0,0,1.3726,.7977,2.7392,2.3882,1.6613,1.9589,6.1481,8.3969,8.0101,10.6484,1.8581,2.2574,4.2377,4.7766,6.7879,4.891v.8801c-1.2223,.2675-3.1812,.5001-4.6797,.5001-3.1995,0-5.7535-1.1302-8.2339-4.132-2.147-2.6122-5.7886-8.0324-7.9317-10.7715-1.3715-1.7438-3.0328-3.1065-6.0734-3.6067-.5874-.1008-1.1437-.1842-1.8096-.2627v13.5495Z" fill="#fff"/><path d="M444.6967,136.945c-.8587-1.9017-2.1779-3.2955-4.4257-3.7899v-1.1088c1.3977,0,6.2402,.1754,7.3045,.1754,.978,0,5.2108-.1754,6.6482-.1754v1.0778c-1.2755,.2453-2.7305,.9509-2.7305,2.2564,0,.9335,.5652,2.2041,1.6478,4.5973l10.1493,23.093,9.6055-23.1328c.758-1.8668,1.3057-3.313,1.3057-4.417,0-1.2222-1.1263-2.0684-2.7217-2.397v-1.0778c1.2755,0,4.4044,.1754,5.3775,.1754,.8888,0,4.5614-.1754,5.964-.1754v1.1088c-2.397,.6485-3.8567,1.9677-5.2021,5.0916l-14.1369,33.3343h-3.1986l-15.5869-34.6361Z" fill="#fff"/><path d="M480.9408,31.8195c-1.6342-3.6067-4.1408-6.2358-8.3871-7.1779v-2.099c2.6422,0,11.4152,.3155,13.4312,.3155,1.8581,0,10.3547-.3155,13.063-.3155v2.0461c-2.4019,.4692-5.1624,1.8102-5.1624,4.2862,0,1.7481,1.0865,4.163,3.1027,8.6896l19.2507,43.7636,18.2155-43.8383c1.42-3.5495,2.4803-6.262,2.4803-8.361,0-2.3311-2.1556-3.9129-5.1749-4.5401v-2.0461c2.4096,0,8.2688,.3155,10.1308,.3155,1.6924,0,8.6508-.3155,11.2978-.3155v1.9807c-4.5401,1.2314-7.318,3.8388-9.8468,9.7591l-26.7791,63.1851h-6.0598l-29.5619-65.648Z" fill="#fff"/><path d="M221.7283,95.0618c3.4966-.7978,5.9552-2.3883,5.9552-6.3498V30.7853c0-3.8034-2.2875-5.3814-5.9552-6.3367v-2.0553c1.8358,0,9.7455,.3112,11.6696,.3112,2.2172,0,10.5079-.3112,12.3311-.3112v2.0553c-3.4927,.7933-6.0827,2.3796-6.0827,6.3367v24.1979h43.1545V30.7853c0-3.957-2.3001-5.5433-5.9465-6.3367v-2.0553c1.8232,0,9.9651,.3112,12.1779,.3112,1.9104,0,10.0044-.3112,11.8097-.3112v2.0553c-3.4967,.7933-6.0866,2.3796-6.0866,6.3367v57.9267c0,3.8034,2.4319,5.3989,6.0866,6.3498v1.8968c-1.8053,0-9.8993-.157-11.8097-.157-2.2129,0-10.3547,.157-12.1779,.157v-1.8968c3.471-.7978,5.9465-2.3883,5.9465-6.3498v-27.3753h-43.1545v27.3753c0,3.9614,2.4275,5.3989,6.0827,6.3498v1.8968c-1.8232,0-10.1138-.157-12.3311-.157-1.924,0-9.8338,.157-11.6696,.157v-1.8968Z" fill="#fff"/><path d="M739.7902,91.2448c2.7033,.4909,7.6989,.7977,11.6381,.7977,22.301,0,33.909-13.4226,33.909-32.1426,0-19.4083-12.2477-33.0629-33.0977-33.0629-4.26,0-9.5832,.3198-12.4494,.7846v63.6232Zm-18.8999,3.817c4.478-.7978,6.9458-2.5768,6.9458-6.6653V30.7853c0-3.9701-2.4328-5.5433-6.7617-6.3367v-2.0553c2.4931,0,10.6087,.3112,12.8565,.3112,3.6289,0,13.7511-.7928,21.6303-.7928,26.5465,0,42.6636,14.8245,42.6636,37.3659,0,21.9104-16.7704,38.1463-44.1407,38.1463-7.8918,0-17.2522-.6222-20.915-.6222-2.2265,0-9.7945,.315-12.2788,.315v-2.0548Z" fill="#fff"/><path d="M420.4066,57.8052c2.3621,.3112,5.8545,.4687,9.3167,.4687,13.9614,0,18.3473-8.0368,18.3473-15.1357,0-10.0829-6.7132-16.3012-18.9435-16.3012-2.5201,0-6.1917,.3198-8.7206,.7846v30.1836Zm0,30.3809c0,3.8388,2.4319,5.9247,6.9061,6.8756v2.0548c-2.493,0-10.6135-.315-12.9485-.315-1.9725,0-9.9389,.315-12.4279,.315v-2.0548c4.1543-.7978,6.6036-2.8661,6.6036-6.8756V30.9869c0-3.5189-1.9017-5.7449-6.595-6.5382v-2.0553c2.4939,0,10.3636,.3112,12.5725,.3112,3.6503,0,14.0012-.6087,18.0847-.6087,17.8531,0,27.791,7.384,27.791,20.0126,0,9.9563-7.4139,16.6565-18.7942,19.4214,0,0,2.5812,1.5033,5.1789,4.5313,3.1511,3.7027,11.8454,16.1481,15.3601,20.4114,3.5136,4.2682,8.0227,9.0362,12.8438,9.2552v1.6788c-2.3098,.4991-6.0085,.9246-8.835,.9246-6.086,0-10.9198-2.1305-15.6217-7.8268-4.0535-4.9433-11.1438-15.4512-15.206-20.6398-2.5937-3.3043-5.7226-5.8806-11.4675-6.8314-1.1311-.1928-2.1954-.3421-3.4448-.4822v25.6353Z" fill="#fff"/><path d="M655.7067,57.8052c2.3921,.3112,5.8631,.4687,9.3292,.4687,13.9663,0,18.3396-8.0368,18.3396-15.1357,0-10.0829-6.718-16.3012-18.926-16.3012-2.5425,0-6.1966,.3198-8.7428,.7846v30.1836Zm0,30.3809c0,3.8388,2.4406,5.9247,6.9196,6.8756v2.0548c-2.4891,0-10.6009-.315-12.9359-.315-2.0073,0-9.9476,.315-12.4454,.315v-2.0548c4.1455-.7978,6.5998-2.8661,6.5998-6.8756V30.9869c0-3.5189-1.9192-5.7449-6.5862-6.5382v-2.0553c2.5017,0,10.346,.3112,12.5724,.3112,3.6581,0,14.0041-.6087,18.0625-.6087,17.8831,0,27.791,7.384,27.791,20.0126,0,9.9563-7.3966,16.6565-18.7855,19.4214,0,0,2.5938,1.5033,5.1701,4.5313,3.1812,3.7027,11.8756,16.1481,15.3766,20.4114,3.5282,4.2682,8.0373,9.0362,12.8312,9.2552v1.6788c-2.2788,.4991-5.9988,.9246-8.7952,.9246-6.0996,0-10.9547-2.1305-15.6441-7.8268-4.0535-4.9433-11.1215-15.4512-15.2186-20.6398-2.5948-3.3043-5.7139-5.8806-11.4461-6.8314-1.1477-.1928-2.2003-.3421-3.4661-.4822v25.6353Z" fill="#fff"/><path d="M359.781,67.1346l-11.8842-27.6903-11.0692,27.6903h22.9534Zm-47.5851,27.9136c4.7238-1.104,7.3181-4.163,9.0404-8.2558l23.8994-57.5056c1.0168-2.3795,2.2003-7.27,2.2003-7.27h6.687s1.1961,4.9035,2.191,7.2875l25.2579,57.6461c1.8014,3.9701,3.7511,6.8358,8.7729,8.0978l-.0126,1.9153c-2.7348,0-11.2358-.158-13.1686-.158-1.9235,0-10.0437,.158-12.7735,.158l.0086-1.9153c3.6765-.9024,4.8382-2.7735,4.8382-4.5837,0-1.5377-.6359-3.2732-1.4069-5.0741l-5.4294-12.3839h-27.8308l-4.9733,12.4537c-.5564,1.4113-1.2184,3.4051-1.2184,4.7505,0,2.0771,1.0866,3.7336,5.2584,4.8376l-.0087,1.9153c-2.4711,0-8.9964-.158-10.5254-.158l-10.8108,.158,.0044-1.9153Z" fill="#fff"/><path d="M596.5577,67.1346l-11.893-27.6903-11.0604,27.6903h22.9534Zm-47.5855,27.9136c4.7203-1.104,7.3228-4.163,9.0365-8.2558l23.908-57.5056c1.0169-2.3795,2.2129-7.27,2.2129-7.27h6.687s1.1835,4.9035,2.1741,7.2875l25.267,57.6461c1.7874,3.9701,3.755,6.8358,8.7555,8.0978l-.0087,1.9153c-2.7256,0-11.2358-.158-13.1821-.158-1.9057,0-10.0213,.158-12.7557,.158v-1.9153c3.6988-.9024,4.8425-2.7735,4.8425-4.5837,0-1.5377-.6271-3.2732-1.3851-5.0741l-5.4512-12.3839h-27.8307l-4.9783,12.4537c-.5563,1.4113-1.2135,3.4051-1.2135,4.7505,0,2.0771,1.0865,3.7336,5.2583,4.8376v1.9153c-2.4803,0-8.9958-.158-10.5341-.158l-10.8112,.158,.0087-1.9153Z" fill="#fff"/></g><g><path d="M1.2373,1.0646H167.4606V63.8586c0,28.7655-10.7091,89.7824-82.485,135.1901,0,0-77.783-32.4809-83.7383-135.1901V1.0646Z" fill="#a51c30"/><path d="M84.8064,200l-.4683-.1944C83.555,199.478,5.9275,165.916,.0037,63.814l-.0037-63.814H168.1782V63.7566c0,25.1095-8.086,88.6236-82.9423,135.9731l-.4295,.2703ZM1.9511,1.9511V63.7566c5.6165,96.7558,76.2817,131.1341,82.6794,134.046,73.6401-46.7998,81.5928-109.3068,81.5928-134.046V1.9511H1.9511Z" fill="#1f1f1f"/><path d="M127.0489,81.7494s-1.4791,4.7242-8.073-.1296l-22.6252-.5442s-2.9637,.9534-3.3673-2.1492c0,0,.5442-6.1941,.2647-6.7346,0,0,.1388-1.7494-2.8305-1.7494,0,0-4.5817,.5368-4.7094-3.5061,0,0-.8034-4.3096,5.5202-4.1744,0,0,2.0196,.9441,2.1585-1.6198,0,0-.2703-17.5122-.1388-18.8487,0,0,.5443-1.6142-2.5565-1.8845,0,0-4.4465,.9367-4.9834-2.0159,0,0-.2721-4.4465,2.6953-4.7205,0,0,3.6376,.274,4.3077-.6738,0,0,.8164,.5331,.6757-2.6879l.1407-5.5295s.3887-1.4791,2.6842-1.3384c0,0,4.1763,.2684,4.7187-.1407,0,0,.9367-1.2088,1.2125-1.7531,0,0,2.1548-.1277,2.5546,.4073,0,0,3.2377,2.1548,15.4889,1.3458,0,0,1.8901,0,2.2899,.5442,0,0,2.2881,1.7457,3.6376-.1351,0,0,2.0141-.4091,8.0767-.2684,0,0,6.5995,1.7475,11.1774-2.0215l1.4847,.2647s1.8845,3.0952,3.2322,2.1603c0,0,4.0393-.4036,4.7131,.4017,0,0,1.3403,2.0122,.6701,7.2752,0,0-.8034,2.2844,3.1044,2.2844,0,0,4.4465-.809,3.8986,3.3636,0,0,1.2125,4.7187-6.1885,4.0485,0,0-.946,1.344-.8145,2.288,0,0-.1314,15.35-.2684,17.1049,0,0-.1277,2.425,3.0989,2.2936,0,0,4.3133-.2795,4.4521,3.6283,0,0,.535,5.1241-5.6646,4.1744,0,0-1.8864,.2703-2.1585,1.4828l-.2629,6.7346s.1333,3.3673-3.6357,2.5583c-.5387,0-21.0072,.4054-22.7603-.1314,0,0-.9515-.137-1.2199,.3961" fill="#fff"/><path d="M83.5491,104.2625s.9404-.398,1.2088-1.0644c0,0,2.8305-.2758,3.2303-.6757l8.8949,.6757s8.7487,.6664,12.5214-2.0382c0,0,1.3588,0,2.3029,.4128,0,0,1.8752,.4054,2.4102,1.2088l5.1241-.137s2.9619,.9497,2.6879,2.8416v2.4139s-.5442,4.8501,.8053,5.1204h3.9171s3.2285,1.4846,2.8249,3.3673c0,0,.1351,2.6879-2.6842,3.2303,0,0-2.8397,.8034-3.7727,.6794,0,0-.9497,1.2088-1.0904,2.6879l-.3961,17.6473s-.2777,1.8808,2.5546,1.6142c0,0,4.1689-.3999,5.3888,1.8919,0,0,1.0811,3.9023-1.0755,4.5761l-1.6087,.8016-3.5136,.5498s-1.4754,.1333-1.6105,2.6879v4.7094s.1351,3.2377-2.4269,3.2377l-3.769,.2703s-.9441,.8034-2.8286,.2647c0,0-22.8936,.411-23.7063,.1333l-2.7009,.5461s-2.9563,2.6953-5.3832,.6646l-1.8845-1.4846s-1.344,.274-1.8827,.1407c-.5405-.1407-25.3242,.274-25.3242,.274,0,0-5.2537,.5405-5.6535-1.2144,0,0-.6701-6.8716-.4017-7.6861,0,0,0-2.0104-1.2144-2.1455,0,0-5.2518-.2647-5.3869-.8127,0,0-2.8342-2.0159-2.0233-4.03,0,0,.9478-2.7046,3.7764-2.9693,0,0,4.3059,.6812,4.3059-.5387,0,0,.274-.809,.274-2.1455,0,0,.2684-16.0387,.1333-17.116,0,0,.3999-2.0215-1.3495-2.0215,0,0-1.8882,.535-3.097-.2684,0,0-3.2285,.1351-3.9041-2.425,0,0-.5442-1.6142,.2647-2.9693,0,0,1.4809-2.9619,5.7924-2.0141,0,0,2.4288,.6794,2.6935-1.0681l-.1277-6.4699s-.5461-1.7512,2.8231-2.6935c0,0,4.3133,1.2107,5.6535-.9441,0,0,1.4846-2.9674,2.6842-.9497,0,0,2.5694,2.4306,9.5762,2.1696,0,0,12.1234-.9497,12.3881-.4165,0,0,2.96,.4165,3.769,1.3514l.8108,.1296Z" fill="#fff"/><path d="M46.9262,81.7494s-1.4846,4.7242-8.0823-.1351l-22.6252-.5387s-2.9637,.9534-3.3692-2.1511c0,0,.5405-6.1922,.2647-6.7328,0,0,.1407-1.7531-2.8231-1.7531,0,0-4.578,.5461-4.7094-3.4969,0,0-.8108-4.3188,5.5184-4.18,0,0,2.0141,.9441,2.1548-1.6105,0,0-.2721-17.5159-.1407-18.8654,0,0,.5498-1.5994-2.5546-1.8715,0,0-4.4484,.9311-4.9778-2.0326,0,0-.274-4.4354,2.6879-4.7094,0,0,3.6339,.274,4.3133-.6627,0,0,.8071,.5239,.672-2.7101l.1351-5.5128s.4036-1.4846,2.6879-1.3495c0,0,4.1781,.2629,4.7224-.1351,0,0,.946-1.2088,1.2014-1.7531,0,0,2.164-.1222,2.5676,.4036,0,0,3.2285,2.1548,15.4981,1.3495,0,0,1.8752,0,2.2844,.5405,0,0,2.2844,1.7475,3.6283-.1425,0,0,2.0215-.398,8.0841-.2629,0,0,6.5902,1.7438,11.1756-2.0104l1.4791,.2666s1.8827,3.0933,3.2396,2.1492c0,0,4.0374-.4054,4.7187,.4054,0,0,1.3421,2.0215,.6627,7.2752,0,0-.8034,2.2899,3.0989,2.2899,0,0,4.4447-.8034,3.9078,3.3581,0,0,1.2162,4.7187-6.1922,4.0485,0,0-.9478,1.3495-.8145,2.288,0,0-.1333,15.35-.2684,17.1049,0,0-.1296,2.4195,3.0989,2.2936,0,0,4.3114-.2832,4.4465,3.6339,0,0,.5313,5.1185-5.6535,4.1689,0,0-1.8919,.2758-2.1622,1.4828l-.2647,6.7328s.1407,3.3692-3.6413,2.5657c-.5387,0-21.0054,.398-22.7584-.1314,0,0-.9367-.1425-1.2107,.3906" fill="#fff"/><path d="M127.0489,81.7494s-1.4791,4.7242-8.073-.1296l-22.6252-.5442s-2.9637,.9534-3.3673-2.1492c0,0,.5442-6.1941,.2647-6.7346,0,0,.1388-1.7494-2.8305-1.7494,0,0-4.5817,.5368-4.7094-3.5061,0,0-.8034-4.3096,5.5202-4.1744,0,0,2.0196,.9441,2.1585-1.6198,0,0-.2703-17.5122-.1388-18.8487,0,0,.5443-1.6142-2.5565-1.8845,0,0-4.4465,.9367-4.9834-2.0159,0,0-.2721-4.4465,2.6953-4.7205,0,0,3.6376,.274,4.3077-.6738,0,0,.8164,.5331,.6757-2.6879l.1407-5.5295s.3887-1.4791,2.6842-1.3384c0,0,4.1763,.2684,4.7187-.1407,0,0,.9367-1.2088,1.2125-1.7531,0,0,2.1548-.1277,2.5546,.4073,0,0,3.2377,2.1548,15.4889,1.3458,0,0,1.8901,0,2.2899,.5442,0,0,2.2881,1.7457,3.6376-.1351,0,0,2.0141-.4091,8.0767-.2684,0,0,6.5995,1.7475,11.1774-2.0215l1.4847,.2647s1.8845,3.0952,3.2322,2.1603c0,0,4.0393-.4036,4.7131,.4017,0,0,1.3403,2.0122,.6701,7.2752,0,0-.8034,2.2844,3.1044,2.2844,0,0,4.4465-.809,3.8986,3.3636,0,0,1.2125,4.7187-6.1885,4.0485,0,0-.946,1.344-.8145,2.288,0,0-.1314,15.35-.2684,17.1049,0,0-.1277,2.425,3.0989,2.2936,0,0,4.3133-.2795,4.4521,3.6283,0,0,.535,5.1241-5.6646,4.1744,0,0-1.8864,.2703-2.1585,1.4828l-.2629,6.7346s.1333,3.3673-3.6357,2.5583c-.5387,0-21.0072,.4054-22.7603-.1314,0,0-.9515-.137-1.2199,.3961" fill="#1f1f1f"/><path d="M127.0489,81.7494s-1.4789,4.7246-8.0738-.1295l-22.6245-.5438s-2.9637,.9524-3.3665-2.1494c0,0,.5438-6.1949,.2647-6.7358,0,0,.1381-1.7494-2.8313-1.7494,0,0-4.5807,.5381-4.7102-3.5046,0,0-.8028-4.3102,5.5216-4.175,0,0,2.0199,.9438,2.158-1.6199,0,0-.2705-17.5114-.1381-18.8494,0,0,.5438-1.6142-2.5579-1.8847,0,0-4.4455,.938-4.9835-2.0141,0,0-.2705-4.4484,2.6961-4.7217,0,0,3.6369,.2733,4.3074-.6733,0,0,.8172,.5323,.6762-2.6874l.141-5.5302s.3884-1.479,2.6845-1.338c0,0,4.175,.2676,4.7188-.141,0,0,.9351-1.2085,1.2114-1.7523,0,0,2.1551-.1295,2.5551,.4057,0,0,3.237,2.1551,15.4887,1.3466,0,0,1.8904,0,2.2904,.5438,0,0,2.2875,1.7465,3.6369-.1352,0,0,2.0141-.4086,8.0767-.2676,0,0,6.6006,1.7465,11.1784-2.0228l1.4847,.2647s1.8846,3.096,3.2312,2.1609c0,0,4.0398-.4028,4.7131,.4028,0,0,1.3408,2.0113,.6704,7.2739,0,0-.8028,2.2846,3.1046,2.2846,0,0,4.4455-.8085,3.8988,3.3636,0,0,1.2114,4.7188-6.1891,4.0484,0,0-.9466,1.3437-.8143,2.2875,0,0-.1324,15.3506-.2676,17.1057,0,0-.1295,2.4256,3.0989,2.2932,0,0,4.3131-.2791,4.4512,3.6283,0,0,.5352,5.1245-5.6655,4.175,0,0-1.8847,.2705-2.158,1.4818l-.2618,6.7358s.1324,3.3665-3.6369,2.5579c-.5381,0-21.0074,.4057-22.7597-.1324,0,0-.9524-.1352-1.22,.3971Z" fill="none" stroke="#1f1f1f" stroke-width=".3109"/><path d="M101.5983,26.2613s.2684,2.699,.2684,3.3784c0,.672-.398,38.9193-.398,38.9193,0,0,.398,2.96-2.1492,4.441,0,0-.6812,.2647-.8145-1.6161l.2647-40.3984s.2703-4.9889,2.8286-4.7242" fill="#fff"/><path d="M101.5984,26.2612s.2676,2.6989,.2676,3.378c0,.6733-.3971,38.9188-.3971,38.9188,0,0,.3971,2.9608-2.1494,4.4426,0,0-.6819,.2647-.8143-1.6171l.2647-40.3977s.2705-4.9893,2.8284-4.7246Z" fill="none" stroke="#1f1f1f" stroke-width=".3264"/><path d="M97.1586,73.4053s.2647-37.9807,.1351-38.6564c-.1351-.6646,.1296,.5424,.1296,.5424,0,0-.3999-6.5995,1.3458-9.3022,0,0-.5405-2.2788-3.6357,.5479l-.1296,5.5184s0,3.1044-2.8286,2.9693c0,0-3.234-.1444-4.7187,1.3384,0,0-.809,2.9656,2.2936,2.4343,0,0,4.8445,0,5.1185,2.0104l-.274,20.3427s1.0829,3.3747-2.6879,3.3747c0,0-4.5891-.2851-4.4502,2.5472,0,0,.9515,2.4232,4.8538,1.6161,0,0,2.8231,.5331,2.6935,3.2377v5.113s-.2758,2.0289,2.4195,2.1603h21.0109s1.0718,.1351,1.0718-1.2162c0,0-.1296-1.0755-1.7438-1.0755l-17.5085-.2684s-2.8305,.946-3.0952-3.234" fill="#fff"/><path d="M101.1992,73.3424s-.5387,1.8845,1.4791,1.4884h13.8691l3.769,.8127s3.9023-.9478,0-3.0989c0,0-12.3863,.124-13.4655-.1351,0,0-2.5583-.6757-3.1044-.8108,0,0-1.3384-.535-2.5472,1.7438" fill="#fff"/><path d="M101.1993,73.3424s-.5381,1.8847,1.4789,1.4876h13.8687l3.7693,.8143s3.9017-.9495,0-3.0989c0,0-12.3869,.1237-13.4659-.1352,0,0-2.5579-.6762-3.1046-.8114,0,0-1.338-.5352-2.5464,1.7437Z" fill="none" stroke="#1f1f1f" stroke-width=".3264"/><path d="M124.2194,75.2262s-2.5583,0-2.4232,3.3747c0,0,.2684,2.5583,2.9638,2.5583,0,0,2.4232-.4054,2.1622-3.0952,0,0-1.4884-3.371-2.7027-2.8379" fill="#fff"/><path d="M126.1132,73.8902s1.2088-1.344,2.0196-1.344c0,0,13.4711,1.2088,15.748-.4017,0,0,2.0289-.4091,2.5694,0,0,0,2.0178,1.6105,2.0178,2.5491,0,0-.137,1.2218-2.5583,.5313,0,0-15.2241,.1462-16.0294,.1462,0,0-4.1818,.9386-3.7672-1.481" fill="#fff"/><path d="M126.1132,73.8903s1.2085-1.3437,2.0199-1.3437c0,0,13.4717,1.2085,15.7476-.4028,0,0,2.0285-.4086,2.5695,0,0,0,2.017,1.6113,2.017,2.5493,0,0-.1352,1.2229-2.5579,.5323,0,0-15.2239,.1467-16.0296,.1467,0,0-4.1808,.938-3.7664-1.4818Z" fill="none" stroke="#1f1f1f" stroke-width=".3264"/><path d="M127.8612,78.254s0-1.0811,1.8882-1.0811l18.8487-.1333s1.7586,.9441,1.7586-2.2881c0,0,.6849-14.6762,.7534-30.8463,.0167-4.8112,.2388-9.8612,.0611-14.5373,0,0-.4147-2.0196-.9552-2.4343,0,0,0-2.1492,2.2899-1.3403,0,0,2.0252,.137,1.4847,3.2433l.137,4.6946s-.4073,2.0289,3.2266,1.4884c0,0,3.6357,.5405,3.7709,1.8808,0,0,1.0792,2.7046-3.2248,2.4287h-3.1044s-1.3458,.8053-.9441,2.4251l-.4017,19.5355s-.2721,3.3636,2.9637,3.2359c0,0,3.3636-.1407,4.0356,.9385,0,0,2.3047,3.3673-2.6879,3.0933,0,0-3.0989-.1351-3.7709,.4091,0,0-.5405,.6664-.9441,7.003,0,0,.274,3.7727-2.5546,3.3636,0,0-18.7321,.2666-20.4722-.1333,0,0-1.8901,.5424-2.1585-.946" fill="#fff"/><path d="M103.6228,25.0359l-.4091,43.2455s-.1296,2.0122,3.2377,2.4176c0,0,3.9041,.3999,4.839,0,0,0,2.575-.1388,9.1615,.1388,0,0,1.629,1.6253,1.7586-.4128,0,0,1.07-35.004,.5387-42.2866,0,0-.1388-3.1026-2.4325-3.234,0,0-10.2278,.8182-11.1719,0l-4.043-1.0681s-1.6179,.1296-1.4791,1.1996" fill="#fff"/><path d="M124.8995,27.2009s-.4054,20.3334-.2684,21.0128l-.2703,17.1012-.5424,5.9256s.8127,1.2181,1.481,.4091c0,0,4.317-1.0922,7.0067-.6701,0,0,8.6265,.7997,10.3703-.5516,0,0,1.3514,.672,1.7457-1.4791,0,0,.5331-37.7049,.2814-38.3787,0,0,.522-5.3999,.2518-5.9293,0,0-.1166-1.207-2.4121-.1351,0,0,.2629,1.0774-12.5251,.6646,0,0-4.8446-.1333-5.1185,2.0307" fill="#fff"/><path d="M146.3179,26.67l-.1296,42.5532s1.0737,3.7783,2.8194,3.3803c0,0,.2629-.8145,.3943-2.1603l.5498-40.5446s-1.3551-6.4569-3.6339-3.2285" fill="#fff"/><path d="M146.3178,26.6701l-.1295,42.5529s1.0733,3.7779,2.8198,3.3809c0,0,.2618-.8143,.3942-2.1609l.5496-40.5445s-1.3552-6.4567-3.6341-3.2284Z" fill="none" stroke="#1f1f1f" stroke-width=".3264"/><path d="M129.783,39.4085c-.4091-1.0792,2.2899-1.2107,2.2899-1.2107l1.3477,.2703c.9423-.1388,1.8864,.2703,1.8864,.2703,.9423,1.4791-.6757,2.2881-.6757,2.2881l-.535,1.7494c-.1388,1.4865,0,14.2856,0,14.2856,.2666,.6646,1.3495,1.8734,1.3495,1.8734,0,1.2144-1.4884,.9515-1.4884,.9515l-3.9097,.1351c-1.2107-.1351-.8034-1.4865-.8034-1.4865,1.344-.6738,1.7494-3.1063,1.7494-3.1063v-13.3267l-1.2107-2.6935Z" fill="#1f1f1f"/><path d="M111.6034,51.9374l-.2721,4.1744,1.2088,2.0141c.8145,1.0829-.5424,1.8938-.5424,1.8938l-4.304-.4054c-.8016-.4054,0-1.7531,0-1.7531,1.0829-.6701,1.2125-2.425,1.2125-2.425l-.1296-7.812,.1296-5.6591c0-.6738-1.0737-1.8827-1.0737-1.8827-.9404-.1296-.6757-1.344-.6757-1.344,.2703-.6757,2.5509-.2703,2.5509-.2703h5.6628c5.3869,1.7475,4.5817,5.6535,4.5817,5.6535,.4073,3.906-3.7672,5.5313-3.7672,5.5313l-.2758,2.1492,3.9097,6.1885c.6757,.5442,.5405,1.0848,.5405,1.0848-.5405,1.4828-2.7009,0-2.7009,0l-4.8427-7.5436c-.4054-.5387-1.2125,.4054-1.2125,.4054m.1333-10.6462c.1296,2.973,.1296,7.0123,.1296,7.0123,2.5657,2.0159,4.043-.8182,4.043-.8182,3.3636-3.2211,0-6.1941-.5387-6.9938-.5498-.8182-3.234-.1444-3.234-.1444l-.3999,.9441Z" fill="#1f1f1f"/><path d="M83.5491,104.2625s.9404-.398,1.2088-1.0644c0,0,2.8305-.2758,3.2303-.6757l8.8949,.6757s8.7487,.6664,12.5214-2.0382c0,0,1.3588,0,2.3029,.4128,0,0,1.8752,.4054,2.4102,1.2088l5.1241-.137s2.9619,.9497,2.6879,2.8416v2.4139s-.5442,4.8501,.8053,5.1204h3.9171s3.2285,1.4846,2.8249,3.3673c0,0,.1351,2.6879-2.6842,3.2303,0,0-2.8397,.8034-3.7727,.6794,0,0-.9497,1.2088-1.0904,2.6879l-.3961,17.6473s-.2777,1.8808,2.5546,1.6142c0,0,4.1689-.3999,5.3888,1.8919,0,0,1.0811,3.9023-1.0755,4.5761l-1.6087,.8016-3.5136,.5498s-1.4754,.1333-1.6105,2.6879v4.7094s.1351,3.2377-2.4269,3.2377l-3.769,.2703s-.9441,.8034-2.8286,.2647c0,0-22.8936,.411-23.7063,.1333l-2.7009,.5461s-2.9563,2.6953-5.3832,.6646l-1.8845-1.4846s-1.344,.274-1.8827,.1407c-.5405-.1407-25.3242,.274-25.3242,.274,0,0-5.2537,.5405-5.6535-1.2144,0,0-.6701-6.8716-.4017-7.6861,0,0,0-2.0104-1.2144-2.1455,0,0-5.2518-.2647-5.3869-.8127,0,0-2.8342-2.0159-2.0233-4.03,0,0,.9478-2.7046,3.7764-2.9693,0,0,4.3059,.6812,4.3059-.5387,0,0,.274-.809,.274-2.1455,0,0,.2684-16.0387,.1333-17.116,0,0,.3999-2.0215-1.3495-2.0215,0,0-1.8882,.535-3.097-.2684,0,0-3.2285,.1351-3.9041-2.425,0,0-.5442-1.6142,.2647-2.9693,0,0,1.4809-2.9619,5.7924-2.0141,0,0,2.4288,.6794,2.6935-1.0681l-.1277-6.4699s-.5461-1.7512,2.8231-2.6935c0,0,4.3133,1.2107,5.6535-.9441,0,0,1.4846-2.9674,2.6842-.9497,0,0,2.5694,2.4306,9.5762,2.1696,0,0,12.1234-.9497,12.3881-.4165,0,0,2.96,.4165,3.769,1.3514l.8108,.1296Z" fill="#1f1f1f"/><path d="M83.5463,104.1008s.938-.3971,1.2114-1.0646c0,0,2.8284-.2791,3.2284-.679l8.891,.679s8.7528,.6675,12.525-2.0371c0,0,1.3581,0,2.3019,.4115,0,0,1.8789,.4057,2.4112,1.2056l5.1217-.1352s2.9665,.9495,2.6932,2.8399v2.417s-.5438,4.8512,.8057,5.1216h3.9103s3.2312,1.4847,2.8284,3.3665c0,0,.1381,2.6874-2.6845,3.2284,0,0-2.8399,.8057-3.7722,.6819,0,0-.9524,1.2085-1.0876,2.6874l-.3999,17.6467s-.2733,1.8789,2.5551,1.6113c0,0,4.1693-.3942,5.3893,1.8933,0,0,1.0819,3.9017-1.0733,4.575l-1.6113,.8085-3.5132,.5438s-1.4761,.1324-1.6113,2.6874v4.7159s.1352,3.2312-2.4285,3.2312l-3.7664,.2705s-.9438,.8028-2.8284,.2647c0,0-22.8978,.4115-23.7035,.1352l-2.7047,.5438s-2.9521,2.6961-5.3806,.6647l-1.8875-1.4847s-1.3437,.2762-1.8818,.141c-.5409-.141-25.3205,.2762-25.3205,.2762,0,0-5.254,.5381-5.6568-1.2171,0,0-.6704-6.8682-.4-7.6825,0,0,0-2.0113-1.2171-2.1494,0,0-5.2483-.2647-5.3864-.8057,0,0-2.8313-2.0228-2.0228-4.0369,0,0,.9495-2.6989,3.7779-2.9694,0,0,4.3045,.6848,4.3045-.5381,0,0,.2733-.8085,.2733-2.1465,0,0,.2705-16.0382,.1352-17.1115,0,0,.3999-2.0256-1.3523-2.0256,0,0-1.8847,.5352-3.096-.2647,0,0-3.2284,.1352-3.9017-2.4256,0,0-.5467-1.6142,.2647-2.9694,0,0,1.4789-2.9608,5.7892-2.017,0,0,2.4313,.679,2.6961-1.0675l-.1295-6.4682s-.5438-1.7494,2.8255-2.6961c0,0,4.3131,1.2114,5.654-.9409,0,0,1.4789-2.9665,2.6845-.9524,0,0,2.5695,2.4313,9.5729,2.1724,0,0,12.1222-.9524,12.3869-.4201,0,0,2.9636,.4201,3.7722,1.3523l.8085,.1324Z" fill="none" stroke="#1f1f1f" stroke-width=".3109"/><path d="M87.0502,157.1993s1.6179-.8201,2.699-.5331c1.0755,.2573,16.8347-.1407,16.8347-.1407,0,0,6.866,.5331,7.9453-.4147l1.605-.5368s.6794-.7997,.6794-1.8734c0-1.0903,.137-4.7224,.137-4.7224l.4073-1.3366s-.1333-1.3532,0-37.3236c0,0,.5313-2.8138-1.2236-4.5706,0,0,0-1.0737,.5442-.9423,.5461,.1425,.2721,.1425,.2721,.1425,0,0,2.4213-.6849,2.8212,.2573,0,0,1.0866,3.2229,.1351,5.113,0,0-.2684,3.9134,1.766,3.9134,0,0,.8034,.8127,2.4176,.4054,0,0,3.4987,.4073,3.4987,1.4772,0,0,0,2.4288-2.425,2.0233l-3.2359,.2666s-2.1566,.4165-1.8845,2.96c.274,2.5639-.137,20.8813-.137,20.8813,0,0,0,2.164,3.371,2.0326,0,0,4.1763-.1444,4.1763,1.0644,0,0,1.0755,2.699-1.8845,2.836,0,0-5.6628-.137-5.2518,1.4735,0,0-.411,3.7727-.6794,4.4428,0,0,.5479,3.1044-.1314,3.6431,0,0-.3943,1.7512-4.0337,1.4791,0,0-23.1639-.1277-26.8051,.1314,0,0-2.1585-.2592-1.6179-2.1492" fill="#fff"/><path d="M82.879,154.6408s2.2881,.3962,2.2881,2.5583c0,2.1492,.1351,3.3655-1.2181,3.6339-1.3403,.2666-2.8194-.1333-3.2192-1.8771-.411-1.7568,.2592-3.919,2.1492-4.3151" fill="#fff"/><path d="M85.5693,153.5632s2.4195-1.6253,3.3636-1.3495c0,0,12.2567,.809,16.035,.1444,3.769-.6794,1.4791-.1444,1.4791-.1444,0,0,3.234,0,4.1726-1.2144,0,0,.946-.2592,1.4847,.6794l2.0085,2.1603s.1462,1.3421-2.1474,1.2033c0,0-21.9569,0-22.6233,.1388,0,0-4.1763,.6664-3.7727-1.6179" fill="#fff"/><path d="M85.5693,153.5633s2.4198-1.6257,3.3636-1.3495c0,0,12.2574,.8085,16.0354,.1439,3.7693-.679,1.4789-.1439,1.4789-.1439,0,0,3.2341,0,4.1721-1.2142,0,0,.9466-.259,1.4847,.679l2.0084,2.1609s.1467,1.3408-2.1465,1.2027c0,0-21.9569,0-22.6245,.1381,0,0-4.175,.6675-3.7722-1.6171Z" fill="none" stroke="#1f1f1f" stroke-width=".3264"/><path d="M53.6516,105.7475s.9404,0,.809,1.6179l-.274,40.6761s.4054,2.699-1.8808,4.4484c0,0-1.2199,1.4735-1.2199-.8108l.5461-41.4832s.1314-3.0989,2.0196-4.4484" fill="#fff"/><path d="M53.6516,105.7475s.9409,0,.8085,1.6171l-.2733,40.6768s.4057,2.6989-1.8818,4.4484c0,0-1.22,1.4732-1.22-.8114l.5467-41.4825s.1324-3.0989,2.0199-4.4484Z" fill="none" stroke="#1f1f1f" stroke-width=".3264"/><path d="M51.4979,106.0213s-1.6179,2.9637-1.4809,3.6431l-.137,9.0134s-.1351,5.7923,0,6.4662c.137,.6738-.1351,17.6492-.1351,17.6492,0,0-.1351,3.2229,0,4.3114v7.2677s-.2703,3.234,2.1529,2.4195c0,0,23.7007-.5387,25.1909-.124,0,0,2.1492,.3943,1.3495,1.4735,0,0,0,.946-1.4939,.6738,0,0-11.1756,1.07-21.272,.6757,0,0-6.7383,.3943-7.1437-.4036,0,0-1.0755-.1314-1.0755-4.0448,0,0,0-3.6283-.2592-4.3022,0,0,.2592-1.9067-3.1044-2.2992,0,0-4.7113,.8145-4.8482-2.0141,0,0,.672-2.0196,5.25-1.7549,0,0,3.3692,.5387,2.7027-2.1603l.3962-19.9224s.411-3.5135-1.8845-3.6487c0,0-2.1492-.1185-2.8305,.1351,0,0-3.906,0-3.6339-2.2788,0,0,1.3458-2.4288,5.25-1.8901,0,0,2.9619,.5368,3.0989-2.8231,0,0-.137-6.8734,1.4791-7.1382,0,0,3.3729,.124,2.4288,1.0755" fill="#fff"/><path d="M55.5318,150.5989s1.8882,2.0104,4.9889,1.8901l18.3064,.2647s2.0289,.1388,1.9012,1.2088c0,0-.2851,1.6105-2.6953,1.0792l-22.092-.2684-2.4288,.1444s-1.6179-.2758,.9497-3.3747l1.07-.9441Z" fill="#fff"/><path d="M55.5317,150.5991s1.8875,2.0113,4.9893,1.8904l18.3056,.2647s2.0285,.1381,1.9019,1.2085c0,0-.2849,1.6113-2.6961,1.079l-22.0922-.2676-2.4285,.1439s-1.6171-.2762,.9495-3.3751l1.0704-.9438Z" fill="none" stroke="#1f1f1f" stroke-width=".3264"/><path d="M112.1032,148.8374s1.6179,3.1026,2.425,3.5247c0,0,1.4828,1.7383,1.0792-1.3588l.2703-38.8008s-.4054-1.3403,0-3.4895l-1.6161-2.9674s-1.7549-1.3421-1.7549,.8127l-.2684,41.3499-.1351,.9293Z" fill="#fff"/><path d="M112.1032,148.8373s1.6171,3.1018,2.4256,3.5247c0,0,1.4818,1.7379,1.079-1.3581l.2705-38.8008s-.4057-1.3408,0-3.4902l-1.6171-2.9665s-1.7552-1.3437-1.7552,.8114l-.2676,41.3501-.1352,.9294Z" fill="none" stroke="#1f1f1f" stroke-width=".3264"/><path d="M82.2061,130.3887s.1351,3.2248-.2758,6.3218c-.2221,1.6975,.5442,9.5725-.1388,13.6117,0,0-.124,1.3421-2.96,.1407,0,0-17.2382,.3943-17.7714-.1407,0,0-4.7187,.1407-5.1204-2.2899,0,0,.6701-18.447,.2703-19.1431,0,0-.2703-10.0908,0-11.0294,0,0,.3999-9.2929,.1314-10.3722,0,0,.1351-2.1548-.2647-3.2359,0,0,0-1.3495,2.2881-.5424,0,0,.796,1.4847,5.2481,.8238,0,0,3.2396,.5313,6.3366,.1259,0,0,6.8642-.5368,8.6228,0,0,0,2.6953-.5368,3.4932,2.4325l-.1351,8.347,.809,2.6898,.946-.6646,.3961-2.0252,.1351-8.8912s.5387-1.6198,2.6972-1.8882c0,0,3.3655-.4073,3.9152-.1259,.5331,.2592,7.8009,.6609,9.8353,.2592,2.0104-.4054,2.4102,1.3458,8.4766-1.742,0,0,1.6179,.1296,1.6179,1.2014,0,0-.5535,11.457,0,13.6081,0,0,0,21.0091-.4147,22.4882l.2758,6.7383s.2647,2.9637-4.4391,3.2359c0,0,2.96,.3999-15.6333-.137,0,0-2.96-.1351-6.1922,1.3366,0,0-.6701-.1314-.6701-1.8771,0,0,.5313-6.3255,0-12.5344l-.2647-6.8623-1.2144,.1407Z" fill="#fff"/><path d="M70.0797,120.8336s.4091,9.9668,0,11.3144l-.124,2.1548s.5331,1.4754,1.3403,2.0196c0,0,.6775,1.8808-.946,1.7549,0,0-3.3599-.2795-4.1689-.1499,0,0-1.8938,0,0-2.4084,0,0,.6683-.9515,.5313-3.371,0,0,0-11.3144,.2777-11.9827,0,0,.2647-1.4865-.6831-1.8956l-1.6161,.1388-2.0122,1.8864s-.411,2.027-1.3551-.1296v-1.0848l1.2144-3.2285,.8145-.1425s1.2051,.8145,2.2844,1.0866h6.3366l2.2844-1.0866s.9404,.1425,.6794,1.3514c0,0,.3962,3.1044-1.3532,3.5024,0,0-1.0792-.398-1.6105-1.8845,0,0-1.7586-.9385-1.8938,2.1548" fill="#1f1f1f"/><path d="M99.8395,117.2032s-5.1074-.411-5.237,5.113c0,0-.5554,3.7783,5.113,6.207,0,0,4.1744,2.0104,3.8986,4.5687,0,0-.5368,4.5798-4.9834,2.2899,0,0-2.1492-1.0792-2.0104-2.2899,0,0-.6794-1.4846-1.4846-1.2107,0,0-.9534,.2666-.5331,4.7131,0,0,0,1.7512,2.0178,0l1.07,.2703s3.6376,2.9637,6.7291-.6775c0,0,3.3766-3.0952,.9441-6.8642,0,0-1.7494-2.6898-4.839-4.0374,0,0-2.9693-1.3588-3.6394-3.6431,0,0,.946-4.043,4.5724-1.8919,0,0,1.3514,1.6198,2.1566,1.8919,0,0,1.0792,0,.8053-2.4306l-.2555-2.0085s-.274-1.4995-2.164,0c0,0-1.7512,.6609-2.1603,0" fill="#1f1f1f"/><path d="M83.4165,114.3646c.9385,.6831,1.0737,2.0233,1.0737,2.0233,2.6953,7.1419,4.9852,17.5103,4.9852,17.5103,.672,1.3421,1.8864,2.4288,1.8864,2.4288,2.2899,.8034,0,1.4717,0,1.4717-.9441,.411-4.0356-.124-4.0356-.124-1.6216-.2832-.9552-.809-.9552-.809,.6794-.6794,.1351-3.3784,.1351-3.3784-.1351-1.0663-1.3403-2.8231-1.3403-2.8231-.535-.2721-1.4809,.9441-1.4809,.9441,0,0-1.4791,.5387-1.6198,0-.137-.5461-1.0774-1.0663-1.0774-1.0663-1.6142,0-2.2844,4.0245-2.2844,4.0245,.9404,3.3747,0,2.8249,0,2.8249-.809,1.0848-3.3692,.2832-3.3692,.2832-1.2088-.2832-.3962-1.2236-.3962-1.2236,1.4754-.2647,1.8752-1.8845,1.8752-1.8845,.6794-.9404,4.9797-18.4489,4.9797-18.4489,.4128-.8145,.6794-2.4269,1.6235-1.7531m-2.1492,8.8912c-.1407,.6738-1.0848,4.4447-1.0848,4.4447l.8053,1.3532s2.1548,.1296,2.9637,.1296c.8034,0,.9441-.6627,.9441-1.3532,0-.6646-1.4791-4.7039-1.4791-4.7039l-.6794-.8053-1.4698,.9348Z" fill="#1f1f1f"/><path d="M46.9262,81.7494s-1.4846,4.7242-8.0823-.1351l-22.6252-.5387s-2.9637,.9534-3.3692-2.1511c0,0,.5405-6.1922,.2647-6.7328,0,0,.1407-1.7531-2.8231-1.7531,0,0-4.578,.5461-4.7094-3.4969,0,0-.8108-4.3188,5.5184-4.18,0,0,2.0141,.9441,2.1548-1.6105,0,0-.2721-17.5159-.1407-18.8654,0,0,.5498-1.5994-2.5546-1.8715,0,0-4.4484,.9311-4.9778-2.0326,0,0-.274-4.4354,2.6879-4.7094,0,0,3.6339,.274,4.3133-.6627,0,0,.8071,.5239,.672-2.7101l.1351-5.5128s.4036-1.4846,2.6879-1.3495c0,0,4.1781,.2629,4.7224-.1351,0,0,.946-1.2088,1.2014-1.7531,0,0,2.164-.1222,2.5676,.4036,0,0,3.2285,2.1548,15.4981,1.3495,0,0,1.8752,0,2.2844,.5405,0,0,2.2844,1.7475,3.6283-.1425,0,0,2.0215-.398,8.0841-.2629,0,0,6.5902,1.7438,11.1756-2.0104l1.4791,.2666s1.8827,3.0933,3.2396,2.1492c0,0,4.0374-.4054,4.7187,.4054,0,0,1.3421,2.0215,.6627,7.2752,0,0-.8034,2.2899,3.0989,2.2899,0,0,4.4447-.8034,3.9078,3.3581,0,0,1.2162,4.7187-6.1922,4.0485,0,0-.9478,1.3495-.8145,2.288,0,0-.1333,15.35-.2684,17.1049,0,0-.1296,2.4195,3.0989,2.2936,0,0,4.3114-.2832,4.4465,3.6339,0,0,.5313,5.1185-5.6535,4.1689,0,0-1.8919,.2758-2.1622,1.4828l-.2647,6.7328s.1407,3.3692-3.6413,2.5657c-.5387,0-21.0054,.398-22.7584-.1314,0,0-.9367-.1425-1.2107,.3906" fill="#1f1f1f"/><path d="M46.9262,81.7494s-1.4847,4.7246-8.0824-.1352l-22.6245-.5381s-2.9637,.9524-3.3694-2.1523c0,0,.5409-6.192,.2647-6.733,0,0,.141-1.7523-2.8227-1.7523,0,0-4.5778,.5467-4.7102-3.496,0,0-.8114-4.3189,5.5187-4.1808,0,0,2.0141,.9438,2.1551-1.6113,0,0-.2733-17.5143-.141-18.8638,0,0,.5496-1.5998-2.5551-1.8731,0,0-4.4484,.9323-4.9778-2.0314,0,0-.2733-4.4369,2.6874-4.7102,0,0,3.6341,.2733,4.3131-.6618,0,0,.8085,.5237,.6733-2.7105l.1352-5.513s.4028-1.4847,2.6874-1.3495c0,0,4.1779,.2618,4.7217-.1352,0,0,.9466-1.2085,1.2027-1.7523,0,0,2.1638-.1237,2.5666,.4028,0,0,3.2284,2.1551,15.4973,1.3495,0,0,1.876,0,2.2846,.5409,0,0,2.2846,1.7465,3.6283-.1439,0,0,2.0228-.3971,8.0853-.2618,0,0,6.5891,1.7437,11.1756-2.0113l1.4789,.2676s1.8818,3.0931,3.2399,2.1494c0,0,4.0369-.4057,4.7188,.4057,0,0,1.3408,2.0199,.6618,7.2739,0,0-.8028,2.2904,3.0989,2.2904,0,0,4.4455-.8028,3.9074,3.3579,0,0,1.2171,4.7188-6.192,4.0484,0,0-.9466,1.3495-.8143,2.2875,0,0-.1324,15.3506-.2676,17.1057,0,0-.1295,2.4198,3.0989,2.2932,0,0,4.3102-.282,4.4455,3.6341,0,0,.5323,5.1188-5.654,4.1692,0,0-1.8904,.2762-2.1609,1.4818l-.2647,6.733s.141,3.3694-3.6427,2.5666c-.5381,0-21.0045,.3971-22.7568-.1324,0,0-.938-.141-1.2114,.3913Z" fill="none" stroke="#1f1f1f" stroke-width=".3109"/><path d="M21.4702,26.2681s.2758,2.6879,.2758,3.3599-.411,38.9248-.411,38.9248c0,0,.411,2.973-2.1548,4.4484,0,0-.6701,.2758-.809-1.6105l.2703-40.4039s.2684-4.9871,2.8286-4.7187" fill="#fff"/><path d="M21.4701,26.2681s.2762,2.6874,.2762,3.3607c0,.6704-.4115,38.9245-.4115,38.9245,0,0,.4115,2.9723-2.1551,4.4484,0,0-.6704,.2762-.8085-1.6113l.2705-40.4035s.2676-4.9864,2.8284-4.7188Z" fill="none" stroke="#1f1f1f" stroke-width=".3264"/><path d="M17.0276,73.4053s.2684-37.9807,.1351-38.6601c-.1351-.6664,.1333,.5442,.1333,.5442,0,0-.398-6.5884,1.3458-9.2948,0,0-.5387-2.2899-3.6376,.5387l-.1296,5.5239s0,3.1026-2.8305,2.9675c0,0-3.234-.1444-4.7224,1.3458,0,0-.8016,2.9582,2.2918,2.4269,0,0,4.8501,0,5.1185,2.0048l-.2684,20.3482s1.0829,3.3673-2.6935,3.3673c0,0-4.578-.2684-4.4484,2.5602,0,0,.9478,2.4288,4.8575,1.6179,0,0,2.8249,.535,2.6953,3.2211v5.1259s-.2777,2.0252,2.4213,2.1511h21.0128s1.0737,.1407,1.0737-1.2199c0,0-.137-1.0607-1.7475-1.0607l-17.5029-.274s-2.836,.9404-3.1044-3.234" fill="#fff"/><path d="M20.6651,73.6738s-.535,1.8938,1.4754,1.481h13.8746l3.7727,.8034s3.9153-.9385,0-3.0933c0,0-12.3918,.1351-13.4711-.1314,0,0-2.5528-.6738-3.097-.8053,0,0-1.3495-.5387-2.5546,1.7457" fill="#fff"/><path d="M20.6651,73.6739s-.5352,1.8933,1.4761,1.4818h13.8745l3.7722,.8028s3.916-.938,0-3.0931c0,0-12.3927,.1352-13.4717-.1324,0,0-2.5522-.6733-3.096-.8057,0,0-1.3495-.5381-2.5551,1.7465Z" fill="none" stroke="#1f1f1f" stroke-width=".3264"/><path d="M43.7003,75.5677s-2.5657,0-2.4306,3.3544c0,0,.2666,2.5694,2.96,2.5694,0,0,2.425-.4128,2.1585-3.0989,0,0-1.4884-3.371-2.6879-2.8249" fill="#fff"/><path d="M45.5804,74.2119s1.2088-1.3458,2.0196-1.3458c0,0,13.4655,1.2125,15.7573-.398,0,0,2.0252-.3999,2.5565,0,0,0,2.0215,1.6105,2.0215,2.5528,0,0-.1296,1.2218-2.5528,.5461,0,0-15.2278,.1333-16.0294,.1333,0,0-4.1818,.9367-3.7727-1.4884" fill="#fff"/><path d="M45.5804,74.2119s1.2085-1.3466,2.0199-1.3466c0,0,13.4659,1.2142,15.7563-.3971,0,0,2.0256-.3999,2.5579,0,0,0,2.0199,1.6113,2.0199,2.5522,0,0-.1295,1.2229-2.5522,.5467,0,0-15.2268,.1324-16.0296,.1324,0,0-4.1808,.938-3.7722-1.4876Z" fill="none" stroke="#1f1f1f" stroke-width=".3264"/><path d="M47.7341,78.254s0-1.07,1.8752-1.07l18.8673-.1407s1.7475,.9312,1.7475-2.2918c0,0,.6905-14.6817,.7553-30.85,.0204-4.8075,.2332-9.8575,.0518-14.5336,0,0-.4054-2.0141-.9423-2.4287,0,0,0-2.1548,2.2973-1.3384,0,0,2.0122,.1296,1.4717,3.2229l.137,4.7168s-.4073,2.0159,3.2285,1.4847c0,0,3.632,.5313,3.7672,1.8808,0,0,1.0848,2.699-3.2192,2.4232h-3.0933s-1.3532,.8053-.9497,2.4251l-.4036,19.53s-.2758,3.3636,2.9637,3.2414c0,0,3.3673-.1407,4.0337,.9348,0,0,2.2936,3.371-2.6935,3.097,0,0-3.0915-.1351-3.7709,.4054,0,0-.5331,.6794-.9423,6.9975,0,0,.2721,3.7783-2.5602,3.3729,0,0-18.7173,.2647-20.463-.1388,0,0-1.8901,.5442-2.1585-.9404" fill="#fff"/><path d="M23.4819,25.0458l-.3943,43.2381s-.1314,2.0085,3.2322,2.4139c0,0,3.9097,.4091,4.8445,0,0,0,2.5546-.1296,9.1615,.1407,0,0,1.6179,1.6105,1.7494-.4054,0,0,1.0792-35.017,.5405-42.2921,0,0-.1351-3.0952-2.4306-3.234,0,0-10.2315,.8071-11.1737,0l-4.0356-1.0774s-1.6235,.1314-1.4939,1.2162" fill="#fff"/><path d="M66.1868,26.67l-.1351,42.5587s1.0755,3.7727,2.8305,3.3692c0,0,.2684-.809,.4036-2.1603l.5387-40.5391s-1.3477-6.4662-3.6376-3.2285" fill="#fff"/><path d="M66.1867,26.6701l-.1352,42.5586s1.0761,3.7722,2.8313,3.3694c0,0,.2676-.8085,.4028-2.1609l.5381-40.5387s-1.3466-6.4654-3.6369-3.2284Z" fill="none" stroke="#1f1f1f" stroke-width=".3264"/><path d="M44.7768,27.0284s-.4036,20.3334-.2758,21.0128l-.2573,17.1031-.5424,5.9219s.7997,1.2199,1.4754,.411c0,0,4.317-1.0792,7.0067-.6757,0,0,8.6265,.8164,10.3703-.535,0,0,1.3458,.6646,1.7494-1.4847,0,0,.5368-37.7104,.2721-38.3843,0,0,.5387-5.3888,.2647-5.9219,0,0-.1407-1.2218-2.4195-.1425,0,0,.2647,1.0811-12.5251,.6757,0,0-4.8501-.1333-5.1185,2.0196" fill="#fff"/><path d="M40.6194,39.4844l-1.2162,2.5657s-2.9582,13.0545-4.5706,15.7517c0,0-.2666,2.7046-2.5583,.5368,0,0-5.2592-16.5644-5.5295-17.0994l-1.7494-1.2162s-1.0644-1.4828,.8108-1.6142l4.9834,.1314s1.6142,1.3477-.535,2.8397c0,0,.2647,2.1492,3.0933,10.3611,0,0,.8053,3.097,1.7494,.809l2.699-9.5632-.8145-2.8286s-.8071-1.3477,.4073-1.4828c0,0,2.8268-.2666,3.2303,.809" fill="#1f1f1f"/><path d="M48.4353,41.6425l-.1407,14.2782-.398,1.07s-1.3458,1.7512-.4054,1.8901c0,0-1.2051,.809,8.6154,.9404,0,0,3.7783,.6701,2.8342-4.1781,0,0-.4054-1.7457-1.7586,.809,0,0-.4091,2.1529-5.2444,1.4791,0,0-1.0792-.9404-1.0792-2.0104v-5.9312s-.1407-1.4809,2.1511-1.3347c0,0,2.5583,1.605,2.9674,.92,0,0,.9385-2.1437,0-3.4895,0,0-1.2199-.1277-1.3495,.4017,0,0-.8108,1.6179-3.097,.6738,0,0-1.0774-2.1511-.4054-3.9004,0,0-.2666-3.3729,2.0233-3.1026,0,0,2.6935,.5387,2.9582,1.3514,0,0,.6664,1.6216,1.3514-.2666l-.6849-2.2955s-.3906-.9423-1.07-.6738c0,0-4.578,.6738-5.1185,.1314l-3.6431,.4072s-.5313,1.3458,1.0848,2.0159c0,0,.4091,.2758,.4091,.8145" fill="#1f1f1f"/></g></g></g></svg>

![cs50sql](https://github.com/Nadia-Mas/CS50-s-SQL-2024/assets/88572957/8fc62df6-709d-490c-972c-318716fe9423)
