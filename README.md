<h1 align="center">sidra-bin-api</h1>
<p align="center"> New BIN Checker API </p>

![](https://img.shields.io/badge/SidraELEzz-orange?style=for-the-badge&logo=python.svg) 
<p align="center">
<a href="#"><img title="Made in UAE" src="https://img.shields.io/badge/MADE%20IN-UAE-red.svg?style=for-the-badge&logo=github"></a>

</p>
<p align="center">
<img alt="SidraELEzz' Github Stats" src="https://github-readme-stats.vercel.app/api?username=SidraELEzz&show_icons=true&include_all_commits=true&hide_border=true" />

</p>
<p align="center">
<a href="#"><img title="telegram Num" src="https://img.shields.io/badge/telegram%20Num-SidtaTools-red.svg?style=for-the-badge&logo=telegram"></a>
</p>
<p align="center">
<a href="https://github.com/SidraELEzz/followers"><img title="Followers" src="https://img.shields.io/github/followers/SidraELEzz?color=blue&style=flat-square"></a>
</p>


# Sidra-Bin-API

An API to get BIN details from bins.su ( Unofficial &amp; may not work if bins.su do any changes to their site ) 


([Vercel](https://sidra-bin-api.vercel.app/))

([herok](https://sidra-bin-api.herokuapp.com/))





## API

Send Get Request to `http://yourhost:port/api/{bin}`

## Example

Request to : `https://sidra-bin-api.vercel.app/api/549184`

Response : 

```json
{
"result":true,

"message":"Search Successful @SidraTools",

"data":{


"bin":"549184",

"vendor":"MASTERCARD",

"type":"DEBIT",

"level":"PLATINUM",

"bank":"BANK NIZWA SAOG",

"country":"OMAN",

"countryInfo":{

"name":"OMAN",

"emoji":"",

"unicode":"U+1F1F4 U+1F1F2",

"code":"OM",

"dialCode":"+968"

       }

  }

}

```

#### Errors :

```json
// No Results Found
{"result":false,"message":"No Results Found @SidraTools "}

// Invalid Bin
{"result":false,"message":"Request a Valid BIN"}
```




Your app should now be running on [localhost:3000](http://localhost:3000/).



## Deploy

| :---: |
|[![Deploy to Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/SidraELEzz/sidra-bin-api)|

`Note : Scraping is not a Fair use of Vercel`

## Follow us on social media

[![Github](https://img.shields.io/badge/Github-SidraELEzz-orange?style=for-the-badge&logo=github)](https://github.com/SidraELEzz/)

[![Telegram](https://img.shields.io/badge/Telegram-SidraELEzz-orange?style=for-the-badge&logo=Telegram)](https://t.me/SidraTools)
