---
date: "1"

---
<script>
  window.intercomSettings = {
    app_id: "ywevvpcu"
  };
</script>

<script>
// We pre-filled your app ID in the widget URL: 'https://widget.intercom.io/widget/ywevvpcu'
(function(){var w=window;var ic=w.Intercom;if(typeof ic==="function"){ic('reattach_activator');ic('update',w.intercomSettings);}else{var d=document;var i=function(){i.c(arguments);};i.q=[];i.c=function(args){i.q.push(args);};w.Intercom=i;var l=function(){var s=d.createElement('script');s.type='text/javascript';s.async=true;s.src='https://widget.intercom.io/widget/ywevvpcu';var x=d.getElementsByTagName('script')[0];x.parentNode.insertBefore(s,x);};if(w.attachEvent){w.attachEvent('onload',l);}else{w.addEventListener('load',l,false);}}})();
</script>
![](imgs/Intro.png)

Welcome to Space's documentation. Here you can find quick tips on how to get started using our platform and insight on the platform's technical architecture. 

**Need support or have an idea to share?** talk to our team using the **pop-up chat window** to the right of the screen.

Space is an open-source, user-controlled, and encrypted platform for storing and sharing files. It is built using Open Web protocols like IPFS, Textile, Filecoin, GunDB, Ethereum, and Torus through the open source Space SDK library, built by us to and available for anyone that also wants to create applications or websites powered by the underlying protocols of the Open Web. Made by the team at [Fleek](https://fleek.co/).

In its first Beta release, Space is available as a **browser application**, accessible from any browser through our [Website](https://space.storage).

## Getting Started

Set up your Space account, upload your first file, learn how to share, and make the best out of a storage platform built so that control over your account, files, and privacy rests in your hands only.

!!! info

    The Space web application is currently a Beta release and represents the first public iteration of the platform. Feel free to reach out to us and share any feedback, ideas, bugs, or thoughts via our social media or our website's chat window, also present in this page.

<div class="prev-boxes-list">
<a href="./getting-started/creating-account/" class="prev-box">
<h5>Creating an Account</h5>
<p>With familiar or high privacy options</p>
</a>
<a href="./getting-started/uploading-files/" class="prev-box">
<h5>Uploading Files</h5>
<p>Store files and folders in Space</p>
</a>
<a href="./getting-started/sharing-files/" class="prev-box">
<h5>Sharing Files</h5>
<p>Share privately, or with public links</p>
</a>
<a href="./getting-started/adjusting-settings/" class="prev-box">
<h5>Adjusting Settings</h5>
<p>Personalize your account</p>
</a>
</div>

## Protocol Stack Overview

Learn how we leverage the underlying protocols of the Open Web (IPFS, Filecoin, Textile GunDB, Torus, and Ethereum) to power features in Space like distributed and user-controlled storage, private file sharing, and user-owned accounts that are Ethereum-based.

<div class="prev-boxes-list">
<a href="./protocols-overview/overview/" class="prev-box">
<h5>Open Web Protocols in Space</h5>
<p>Learn about our Open Web stack</p>
</a>
</div>


## Space SDK

The Space web application is built using the Space SDK, a modular JS library that packages the IPFS, Textile, Filecoin, GunDB, and Torus implementations necessary to build Open Web apps into easy to use commands and interfaces. It's open source and designed as a tool that anyone can plug into their websites or applications and implement Web3-enabled functionalities to make their projects more trustless and user-controlled. 

It's the successor of the Space Daemon, our desktop-based library. The Space SDK take the perks of the Daemon (encryption, user-controlled storage, peer-to-peer interactions, etc.) and makes them available on browser and mobile experiences. It's modular, and protocol agnostic, meaning you can use our own implementations (Textile hub for users, for example) or plug in your own layer and still leverage the SDK as an interface to manage it.

<div class="prev-boxes-list">
<a href="./space-sdk/overview/#Introduction" class="prev-box">
<h5>Overview</h5>
<p>Learn about the SDK</p>
</a>
<a href="./space-sdk/overview/#currently-available-apis" class="prev-box">
<h5>Available Modules</h5>
<p>View the current interfaces</p>
</a>
<a href="./space-sdk/overview/#the-space-sdk-versus-the-space-daemon" class="prev-box">
<h5>Space SDK vs Space Daemon</h5>
<p>What are the main differences?</p>
</a>
<a href="./space-sdk/overview/#installing-the-space-sdk" class="prev-box">
<h5>Installing the Space SDK</h5>
<p>How to get started with the SDK</p>
</a>
<a href="./space-sdk/overview/#migrating-from-the-space-daemon" class="prev-box">
<h5>Migrating from Space Daemon</h5>
<p>Learn the corresponding methods</p>
</a>
</div>

## Space Daemon

The Space Daemon is a desktop-focused library that packages together IPFS, Textile Threads/Buckets, and Textile Powergate (Filecoin) into one easy to install and JS interface to make it easy to build peer to peer and privacy focused apps. 

Installing the Space Daemon is easy and comes with all the tools packaged together including IPFS and Textile nodes, and and also exposes gRPC methods specific to the features you want for your app including: 

File Upload (encrypted), File Sharing, Filecoin Markets, and User Controlled Data. You can access same methods using our JS client, so you don't need to worry about gRCP calls.

<div class="prev-boxes-list">
<a href="./space-daemon/getting-started/#installation" class="prev-box">
<h5>Daemon Installation</h5>
<p>Install the Space Daemon</p>
</a>
<a href="./space-daemon/getting-started/#crud-operations" class="prev-box">
<h5>Users API</h5>
<p>Create and authenticate identities</p>
</a>
<a href="./space-daemon/getting-started/#sharing" class="prev-box">
<h5>P2P Sharing</h5>
<p>Integrate Sharing Files Peer to Peer</p>
</a>
</div>

## Other Resources


Join our public [Slack](https://slack.fleek.co/), visit our [GitHub](https://github.com/FleekHQ), follow us on [Twitter](https://twitter.com/spacestorage), and check out the [Blog](https://blog.space.storage)!