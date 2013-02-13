cm_device_rockchip_rk29board
=================================
Add kernel for build with model tabs 
get kernel http://crewrktablets.arctablet.com/?page_id=240
replace http://crewrktablets.arctablet.com/?wpfb_dl=179 with url your model tabs:

    curl -0 http://crewrktablets.arctablet.com/?wpfb_dl=179 > kernel.7z
    7z e kernel.7z
    mv kernel.img ~/android/system/device/rockchip/rk29board/kernel

Fix Compile Now
=================================

![android_4.2.1 output](http://img11.hostingpics.net/pics/377073Screenshotfrom20130213205924.png)
