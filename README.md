# Portfolio

![HTML](https://img.shields.io/badge/-HTML-F05032?style=flat-square&logo=html5&logoColor=ffffff)
![CSS](https://img.shields.io/badge/-CSS-007ACC?style=flat-square&logo=css3)
![JavaScript](https://img.shields.io/badge/-JavaScript-dc8d2d?style=flat-square&logo=javascript&logoColor=ffffff)
![SASS](https://img.shields.io/badge/-Sass-ca6598?style=flat-square&logo=sass&logoColor=ffffff)
![Web Accessibility](https://img.shields.io/badge/-Accessibility-00A98F?style=flat-square&logo=w3c&logoColor=ffffff)
![Cross-browsing](https://img.shields.io/badge/-Cross%20browsing-302683?style=flat-square&logo=googlechrome&logoColor=ffffff)
![Respond web](https://img.shields.io/badge/-Respond%20web-ca6598?style=flat-square&logo=htmlacademy&logoColor=ffffff)

<br>

## link

> [https://designdigit.github.io/desigin-portfolio1](https://designdigit.github.io/desigin-portfolio1)

<br>

## JavaScript

### Check Browser

``` JavaScript
let desktopFlag;

function checkWindowSize(){
	let winw=window.innerWidth;

	if(winw >= 1240){
		desktopFlag=true;
	}
	else{
		desktopFlag=false;
	}

	if(header.classList.contains("menu-open")){
		header.classList.remove("menu-open");
	}

	Array.from(gnbList).forEach(function(item){
		if(item.classList.contains("open")){
			item.classList.remove("open");
		}
	});
}

checkWindowSize();
```

<br>

윈도우의 가로 크기를 winw에 대입합니다.

``` JavaScript
let winw=window.innerWidth;
```
