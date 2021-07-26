# How to check if deposit fee is compromised

**PREVIOUSLY STAKED FUNDS are not affected**

**FEE CHANGE IS BEHIND THE TIMELOCK CONTRACT**

Our system requires users to deposit a fee when staking, therefore it is possible for the chef to edit the deposit fee to 100%, therefore taking 100% of NEW USER STAKING.

Procedure to check:

1\) Please head to our master chef contract site on BSC

​[https://bscscan.com/address/0xe70E9185F5ea7Ba3C5d63705784D8563017f2E57\#readContract](https://bscscan.com/address/0xe70E9185F5ea7Ba3C5d63705784D8563017f2E57#readContract)​

2\) scroll down to 9. poolInfo

3\) query \(type in the number 0 - 22\)

4\) click onto the lpToken to see which currency/farm you are looking at

5\) check if the depositFEEBP is correct \(400 = 4%, 10000 = 100%\)

![](https://gblobscdn.gitbook.com/assets%2F-MT5Nug3dG0o_JI3n0I1%2F-MTJvlXymK3_pg96l7Pa%2F-MTJx2kqRp6YTYrdC16n%2Fimage.png?alt=media&token=a44b496e-354e-40ef-9ec7-f6a7c9265f1c)

