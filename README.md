# PGP_Signature
used to save my PGP public key

## My public key
- The Fingerprint is：D40ADE2D66EB7463C407ACCA4BD6DD250E4DBFF3
- Public key: [ZH_PGP.pub](https://raw.githubusercontent.com/zh826256645/PGP_Signature/main/ZH_PGP.pub)

## Import My Public Key
Download the [public key file](https://raw.githubusercontent.com/zh826256645/PGP_Signature/main/ZH_PGP.pub)
```[shell]
gpg --import ZH_PGP.pub
```
## Verify
Download the [file](https://raw.githubusercontent.com/zh826256645/PGP_Signature/main/ZH_PGP.pub.sig) used to test signatures
```[shell]
gpg --verify ZH_PGP.pub.sig ZH_PGP.pub
```