# SwifTest: Considerate Internet Speed Test for End Users
### Introduction
Web-based speed test systems (STSes) such as SpeedTest.net are extremely popular and important. In this paper, we conduct a comprehensive measurement study of commercial STSes, finding that their reported speed is oftentimes inaccurate, that their test duration is typically 10+ seconds, and that their data usage can reach up to 2 GB over 5G. We also reverse-engineer their speed test logic, whose many design decisions are found to be ad-hoc and non-adaptive. Motivated by the above findings, we develop SwifTest, an innovative STS solution offering accurate, robust, bandwidthefficient, and ready-to-deploy speed test. This demanding job is fulfilled by our principled designs including elastic bandwidth probing, intelligent bandwidth sampling, strategic test server selection, and adaptive multi-homing. Comprehensive real-world tests show that SwifTest significantly outperforms existing STSes in accuracy, duration, and data usage under the same server pool size. In addition, using only 30 test servers, SwifTest achieves similar accuracy compared to SpeedTest.net that employs ∼9,800 servers, while incurring up to 5.6× shorter duration and up to 10.7× less data usage.
<br/>

### SwifTest We Implement

<style>
table th:nth-of-type(1) {
    width: 150px;
    max-width:150px;
    min-width:150px;
}
</style>

|STS|Implementation|
|:----:|------|
|SwifTest|[https://github.com/SwifTestSystem/<br>SwifTestSystem.github.io/tree/master/SwifTest](https://github.com/SwifTestSystem/SwifTestSystem.github.io/tree/master/SwifTest)|


### Representitive Commercial STSes

|STS|Website|Our Implementation|
|:----:|------|------|
|SpeedOf|[https://speedof.me](https://speedof.me/)|[https://github.com/SwifTestSystem/<br>SwifTestSystem.github.io/tree/master/Speedof.me/](https://github.com/SwifTestSystem/SwifTestSystem.github.io/tree/master/Speedof.me/)|
|BWP|[https://www.bandwidthplace.com](https://www.bandwidthplace.com/)|[https://github.com/SwifTestSystem/<br>SwifTestSystem.github.io/tree/master/BandwidthPlace](https://github.com/SwifTestSystem/SwifTestSystem.github.io/tree/master/BandwidthPlace/)|
|SFtest|[https://sourceforge.net/speedtest](https://sourceforge.net/speedtest/)|[https://github.com/SwifTestSystem/<br>SwifTestSystem.github.io/tree/master/SourceForge/](https://github.com/SwifTestSystem/SwifTestSystem.github.io/tree/master/SourceForge/)|
|ATTtest|[http://speedtest.att.com/speedtest](http://speedtest.att.com/speedtest/)|[https://github.com/SwifTestSystem/<br>SwifTestSystem.github.io/tree/master/ATTSpeedTest/](https://github.com/SwifTestSystem/SwifTestSystem.github.io/tree/master/ATTSpeedTest/)|
|Xfinity|[http://speedtest.xfinity.com/](http://speedtest.xfinity.com)|[https://github.com/SwifTestSystem/<br>SwifTestSystem.github.io/tree/master/XFinity/](https://github.com/SwifTestSystem/SwifTestSystem.github.io/tree/master/XFinity/)|
|FAST|[https://fast.com](https://fast.com)|[https://github.com/SwifTestSystem/<br>SwifTestSystem.github.io/tree/master/Fast.com](https://github.com/SwifTestSystem/SwifTestSystem.github.io/tree/master/Fast.com)|
|SpeedTest|[https://speedtest.net](https://speedtest.net)|[https://github.com/SwifTestSystem/<br>SwifTestSystem.github.io/tree/master/SpeedTest.net](https://github.com/SwifTestSystem/SwifTestSystem.github.io/tree/master/SpeedTest.net)|


### Non-flooding STSes

<style>
table th:nth-of-type(1) {
    width: 150px;
    max-width:150px;
    min-width:150px;
}
</style>

|STS|Implementation|
|:----:|------|
|TOPP|[https://github.com/SwifTestSystem/<br>SwifTestSystem.github.io/blob/master/nonFlooding](https://github.com/BERIST/BERIST.github.io/tree/master/nonFlooding/)|
|IGI|[https://github.com/SwifTestSystem/<br>SwifTestSystem.github.io/blob/master/nonFlooding](https://github.com/BERIST/BERIST.github.io/tree/master/nonFlooding/)|
|PathChirp|[https://github.com/SwifTestSystem/<br>SwifTestSystem.github.io/blob/master/nonFlooding](https://github.com/BERIST/BERIST.github.io/tree/master/nonFlooding/)|


