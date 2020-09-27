# What is Colorspace?  
Representing color system into 3-Demensional space by using hue, lightness, chroma as each xyz  
색상, 명도, 채도 등 3가지 요소를 각 축으로 하여 구상되는 색체계를 3차원의 공간으로 옮겨 표현한 개념
EX : RGB colorspace, CMYK colorspace, HSV colorspace, CIE colorspace etc.  

## CIE colorspace  
CIE xyz colorspace  
![CIE xyz colorspace](https://github.com/fanxysonaka/2D-Digital-Compositing/blob/master/Week%204/CIE%20xyz%20colorspace.png?raw=true)  
CIE lab colorspace  
![CIE lab colorspace](https://github.com/fanxysonaka/2D-Digital-Compositing/blob/master/Week%204/CIE%20lab%20colorspace.jpg?raw=true)  
CIE luv colorspace  
![CIE luv colorspace](https://github.com/fanxysonaka/2D-Digital-Compositing/blob/master/Week%204/CIE%20luv%20colorspace.png?raw=true)  

## ACES colorspace  
![ACES](https://github.com/fanxysonaka/2D-Digital-Compositing/blob/master/Week%204/ACES.png?raw=true)  

# What is LUT?  
A set of instructions for remapping pixel values  
수많은 연산처리 과정을 효율적이고 체계적으로 관리하기 위하여 입력값과 출력값을 만들어 놓고 그 값에 따라 결과를 도출하는 방식  

## Why we use LUTs?    
입력값에 따라 도출되는 결과값을 미리 만들어 놓음으로써 작업하는 모든 과정을 효율적으로 관리하기 위함  
![Graph](https://github.com/fanxysonaka/2D-Digital-Compositing/blob/master/Week%204/Graph.PNG?raw=true)  
위 그래프처럼 입력값과 출력값이 존재한다면, 이를 표로 만들어 입력값에 따른 출력값을 고정적으로 분류해 놓음으로써 작업의 효율을 높힐 수 있음  
![Chart](https://github.com/fanxysonaka/2D-Digital-Compositing/blob/master/Week%204/Chart.PNG?raw=true)  

## LUT의 구성요소 3가지  
Hue : 색상  
Saturation : 채도  
Brightness : 조도  

## Type of LUTs
1D LUTs : 입력값과 출력값이 1:1로 매칭되는 시스템으로 색상과 채도 보정 값은 담아낼 수 없음  
![RGB](https://github.com/fanxysonaka/2D-Digital-Compositing/blob/master/Week%204/RGB.PNG?raw=true)  
3D LUTs : 입력값과 출력값을 3D 공간으로 매칭하는 시스템으로 1D LUTs에서 표현하지 못하는 색상과 채도 보정 값까지 담아낼 수 있음  
![3D RGB](https://github.com/fanxysonaka/2D-Digital-Compositing/blob/master/Week%204/3D%20RGB.PNG?raw=true)  

# What is Logspace and what is main difference with sRGB, why and when we use?  
Logspace : 제가 검색한 내용이 이 주제와 맞는 Logspace와 맞는 것인지 분간이 안되어 더이상 조사를 진행하지 못했습니다.  
  
Difference with sRGB : 이 역시도 저의 얄팍한 지식으로는 어떤 의도를 가지고 접근해서 분석해야 하는지 잘 알지 못하겠습니다.  
  
When we use Logspace : 대체 Logspace라고 검색하면 매트랩과 관련된 내용으로 접근해야 하는건지, Log(Logarithmic) Color Space라고 나오는 키워드로 접근해야 하는건지 모르겠습니다. 제일 찾고자 하는 내용과 근접한 내용을 담고 있는 웹사이트를 첨부합니다.  
https://www.rocketstock.com/blog/tips-for-log-color-space-compositing/  
