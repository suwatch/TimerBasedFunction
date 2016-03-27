# Timer Based Function
This exercises timer based Azure Function written in nodejs and c#.  On timer fires, it will perform http post to the `functionOutUrl` setting.  To try, ...

1. Create a [http request bin](http://requestb.in/).  You will need the request `Bin URL` for next step.

2. Click deploy to azure button below.  Enter the request `Bin URL` as `functionOutUrl` setting.
<br/>
<br/>
   <a href="https://azuredeploy.net/" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
  </a>

3. After deployment successfully, you should see POST requests every 15s, 20s from TimerBasedNodeJS and TimerBasedCSharp functions respectively.
