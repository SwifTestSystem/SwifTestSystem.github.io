# SwifTest: Lightweight Internet Speed Test for End Users by Rejection Sampling
### Introduction
A correct estimation of end users’ Internet access bandwidth (or speed) is crucial to many of today’s networked systems. However, it remains a “heavyweight” task that requires considerable time, data usage, and infrastructure support, due to various noises appearing over the live Internet. To combat the noise, the solution of almost all commercial speed test systems (STSes) is to introduce resource redundancy, which forms a major hurdle preventing STSes from becoming a foundational, ubiquitous Internet service. To overcome the hurdle, instead of utilizing highly redundant resources to avoid or largely suppress the generation of noise, we propose to accommodate and exploit the noise through a novel statistical sampling framework, which we call fuzzy rejection sampling, so as to significantly reduce resource redundancy. To fulfill this idea, we develop a novel STS called SwifTest, which incorporates a suite of innovative techniques to realize lightweight speed tests. Using only 30 test servers, SwifTest achieves similar accuracy compared to the state-of-the-art (SpeedTest:net) that employs ~11,000 servers, while incurring 5.6x shorter test duration and 10.7x less data usage.<br/>

### SwifTest We Implement

<style>
table th:nth-of-type(1) {
    width: 100px;
    max-width:100px;
    min-width:100px;
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



|STS|Implementation|
|:----:|------|
|TOPP|[https://github.com/SwifTestSystem/<br>SwifTestSystem.github.io/blob/master/nonFlooding](https://github.com/SwifTestSystem/SwifTestSystem.github.io/tree/master/nonFlooding)|
|IGI|[https://github.com/SwifTestSystem/<br>SwifTestSystem.github.io/blob/master/nonFlooding](https://github.com/SwifTestSystem/SwifTestSystem.github.io/tree/master/nonFlooding)|
|PathChirp|[https://github.com/SwifTestSystem/<br>SwifTestSystem.github.io/blob/master/nonFlooding](https://github.com/SwifTestSystem/SwifTestSystem.github.io/tree/master/nonFlooding)|


