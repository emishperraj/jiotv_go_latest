JioTV Go, an exciting project that allows you to stream Live TV channels on the web and IPTV. It's a web wrapper around the JioTV Android app, utilizing the same API to fetch and stream channels.

Ready to dive in? Download the latest binary for your operating system from here, and explore the documentation to start your JioTV Go adventure! 🚀

Give us 🌟 on GitHub if you like this project!

We have video tutorials for Windows, and Android users. Please watch them if you are unsure about the installation process.

Features 🌟
📺 Stream Live TV channels, just like in the JioTV Android app.
🎬 M3U playlist support for IPTV.
🌐 Web interface for watching Live TV.
📅 EPG (Electronic Program Guide) support in compressed GZipped XML or JSON format.
🎥 Quality selection (Low, Medium, High) supported.
⚙️ Configurable port and host.
🔐 Authentication options using Jio ID/Number with password or Jio number with OTP.
👥 Support for multiple clients simultaneously.
🚀 Written in Go, ensuring it's fast, lightweight, and portable.
💻 Command-line interface for server management and self-update.
🔄 Background start and stop feature.


Steps:
apt update

git clone https://github.com/emishperraj/jiotv_go_latest.git

apt  install docker-compose &&  apt  install docker.io

cd jiotv_go_latest

docker-compose -f docker-compose.yml up -d
