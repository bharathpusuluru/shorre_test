window.onload = (function() {

    var filename = 'https://tympanus.net/codrops/adpacks/cda_sponsor.css?' + new Date().getTime();
    var fileref = document.createElement("link");
    fileref.setAttribute("rel", "stylesheet");
    fileref.setAttribute("type", "text/css");
    fileref.setAttribute("href", filename);
    document.getElementsByTagName("head")[0].appendChild(fileref);

    let cdaSpots = ['ad1','ad2','ad3','ad4','ad5'];
    let cdaSpot = cdaSpots[Math.floor(Math.random() * cdaSpots.length)];

    switch (cdaSpot) {
        case "ad1":
            var cdaLink = 'https://www.ionos.com/hosting/deploy-now?itc=NGZ8GOUU-DWGP1F-HIU3B32&ac=OM.US.USt64K430429T7073a&utm_source=BSA23&utm_medium=display&utm_campaign=PTN-US-MIX-OMAX-EXT-AWR---&photo=&utm_content=BSACodropsSiteSponsor';
            var cdaSponsorName = 'IONOS: Deploy Now. Tailored solutions for static sites & apps.';
            break;
        case "ad2":
            var cdaLink = 'https://www.ionos.com/cloud/cloud-servers?itc=NGZ8GOUU-DWGP1F-HIU3B32&ac=OM.US.USt64K430429T7073a&utm_source=BSA23&utm_medium=display&utm_campaign=PTN-US-MIX-OMAX-EXT-AWR---&photo=&utm_content=BSACodropsSiteSponsor';
            var cdaSponsorName = 'Robust, Reliable, and Flexible Cloud Hosting from IONOS';
            break;
        case "ad3":
            var cdaLink = 'https://www.ionos.com/hosting/deploy-now?itc=NGZ8GOUU-DWGP1F-HIU3B32&ac=OM.US.USt64K430429T7073a&utm_source=BSA23&utm_medium=display&utm_campaign=PTN-US-MIX-OMAX-EXT-AWR---&photo=&utm_content=BSACodropsSiteSponsor';
            var cdaSponsorName = 'IONOS: Deploy static sites and PHP apps via GitHub with Deploy Now.';
            break;
        case "ad4":
            var cdaLink = 'https://cloud.ionos.com/compute?itc=NGZ8GOUU-DWGP1F-HIU3B32&ac=OM.US.USt64K430429T7073a&utm_source=BSA23&utm_medium=display&utm_campaign=PTN-US-MIX-OMAX-EXT-AWR---&photo=&utm_content=BSACodropsSiteSponsor';
            var cdaSponsorName = 'IONOS: Autoscaling that helps you manage real-time traffic spikes.';
            break;
        case "ad5":
            var cdaLink = 'https://www.ionos.com/servers/vps?itc=NGZ8GOUU-DWGP1F-HIU3B32&ac=OM.US.USt64K430429T7073a&utm_source=BSA23&utm_medium=display&utm_campaign=PTN-US-MIX-OMAX-EXT-AWR---&photo=&utm_content=BSACodropsSiteSponsor';
            var cdaSponsorName = 'IONOS: Customizable VPS Servers for all your project needs.';
            break;
        default:
            var cdaLink = 'https://www.elegantthemes.com/affiliates/idevaffiliate.php?id=17972_5_1_16';
            var cdaSponsorName = 'Divi';
    }

    var cda = document.createElement('div');
    cda.id = 'cdawrap';
    cda.className = 'cdawrap';
    cda.innerHTML = '<a href="' + cdaLink + '" class="cda-sponsor-link" target="_blank" rel="nofollow noopener">'+ cdaSponsorName +'</a>';
    //document.getElementsByClassName('frame')[0].appendChild(cda);
    //console.log("CDA inserted");

    const frameElement = document.getElementsByClassName('frame')[0];
    if (frameElement) {
        frameElement.appendChild(cda);
    }

})();