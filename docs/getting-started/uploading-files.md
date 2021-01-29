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

# Uploading Files to Space

In Space, when you upload a file it is stored on distributed Space nodes (running on IPFS/Textile) that only you can access and decrypt. Aside from that first layer of storage, all files are backed up redundantly on [Filecoin](https://filecoin.io/), a decentralized storage network.

Space allows you to:

- Upload one or multiple files.
- Upload folders / directories.
- Create folders in Space to organize files.

## Upload options
### Dropdown Menu
You can upload **one or multiple files at once**, or directly select directories to **upload entire folders** from your device to Space, using the "+ NEW" button on the top left of the application.

![](imgs/dropdown.gif)

### Drag and Drop
Instead of using the **+** dropdown menu, you can also **drag and drop files** and folders directly into Space.

![](imgs/dragdrop.gif)

## File Details
### Information and Actions

![](imgs/clickdetail.gif)

If you click a file in Space, an individual bar will appear on the right hand bar where you'll see the file details, current shared users, and have access to the **preview and download buttons**. Some of these actions are also available if **you right click the file**.

!!! info

    Some of Space's action are greyed out during the initial phase of the Beta, and will be added shortly.

### IPFS Hash

In this details bar you can also find the file's IPFS hash. **The IPFS hash** represents the file's unique content identifier, as it is stored in the IPFS/Textile node. It represents its location by identifying its content, not its location.

![](imgs/ipfshash.gif)