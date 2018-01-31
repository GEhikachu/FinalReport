# FinalReport
##　操作説明
左クリックでスタート
クリックするとバットを振ります。
タイミングを取ってボールに当てましょう

## 作品紹介
流れてくるボールに合わせて左クリックでバットを当てましょう!
前に打ち返すごとにボールは早くなります。
空振りや後ろに打ってしまうとゲームオーバーです。
何球打てるかチャレンジしてみてください。
<!DOCTYPE html>
<html lang="en-us">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
    <title>Unity WebGL Player | BattingGame</title>
    <link rel="shortcut icon" href="TemplateData/favicon.ico">
    <link rel="stylesheet" href="TemplateData/style.css">
    <script src="TemplateData/UnityProgress.js"></script>  
    <script src="Build/UnityLoader.js"></script>
    <script>
      var gameInstance = UnityLoader.instantiate("gameContainer", "Build/Unity17.json", {onProgress: UnityProgress});
    </script>
  </head>
  <body>
    <div class="webgl-content">
      <div id="gameContainer" style="width: 960px; height: 600px"></div>
      <div class="footer">
        <div class="webgl-logo"></div>
        <div class="fullscreen" onclick="gameInstance.SetFullscreen(1)"></div>
        <div class="title">BattingGame</div>
      </div>
    </div>
  </body>
</html>
