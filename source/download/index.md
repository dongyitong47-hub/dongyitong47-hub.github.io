---
layout: page
title: 游戏下载
comments: false
---

<div class="container">
  <!-- 下载标签页（PO版/移动端/相关信息） -->
  <ul class="nav nav-tabs" role="tablist">
    <li role="presentation" class="active"><a href="#po" aria-controls="po" role="tab" data-toggle="tab">PO版下载</a></li>
    <li role="presentation"><a href="#mobile" aria-controls="mobile" role="tab" data-toggle="tab">移动端下载</a></li>
    <li role="presentation"><a href="#info" aria-controls="info" role="tab" data-toggle="tab">相关信息</a></li>
  </ul>

  <!-- 下载内容区 -->
  <div class="tab-content" style="margin-top:20px; padding:20px; background:#fff; border:1px solid #ddd; border-top:0;">
    <!-- PO版下载 -->
    <div role="tabpanel" class="tab-pane active" id="po">
      <h3 style="color:#e63946;">PO版客户端下载</h3>
      <p><strong>适用系统</strong>：Windows 10/11（64位）</p>
      <p><strong>文件大小</strong>：5.2GB</p>
      <p><strong>更新时间</strong>：2024年12月</p>
      <a href="https://download.example.com/game-po.exe" class="btn btn-danger btn-lg">立即下载</a>
      <p style="margin-top:10px; color:#666;">下载前请阅读 <a href="/download/agreement" style="color:#e63946;">用户协议</a></p>
    </div>

    <!-- 移动端下载 -->
    <div role="tabpanel" class="tab-pane" id="mobile">
      <h3 style="color:#2a9d8f;">移动端下载</h3>
      <p><strong>iOS 用户</strong>：<a href="https://apps.apple.com/cn/app/xxx" target="_blank" style="color:#e63946;">App Store 下载</a></p>
      <p><strong>Android 用户</strong>：</p>
      <img src="/images/android-qrcode.png" alt="Android下载二维码" style="width:200px; margin:10px 0;">
      <p>或点击 <a href="https://download.example.com/game-mobile.apk" style="color:#e63946;">直接下载APK</a>（建议在WiFi环境下下载）</p>
    </div>

    <!-- 相关信息（匹配示意图“相关信,息”） -->
    <div role="tabpanel" class="tab-pane" id="info">
      <h3 style="color:#264653;">下载相关说明</h3>
      <ul style="line-height:2;">
        <li>安装前请确保设备存储空间充足（建议预留10GB以上）</li>
        <li>移动端需 Android 8.0+ 或 iOS 12.0+ 系统</li>
        <li>若下载失败，可尝试 <a href="/download/troubleshoot" style="color:#e63946;">下载常见问题排查</a></li>
        <li>PO版需先安装 <a href="https://dotnet.microsoft.com/download/dotnet-framework/net48" target="_blank" style="color:#e63946;">.NET Framework 4.8</a>（否则无法启动）</li>
      </ul>
    </div>
  </div>
</div>
