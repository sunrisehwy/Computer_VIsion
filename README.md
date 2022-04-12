# Geolocation
Market analysis for QANDA, AI-based learning platform

1. Objective
- Confirming QANDA, Al-based learning platform user distribution in Latin America & The Caribbean based on user data for 5 weeks and identifying user's socio-economic status 
- By identifying the socio-economic characteristics of the users, analyzing how the online learning app contributes to the reducing learning gap caused by a regional economic gap or education environment.

2. Process
(1)	Mass Data pre-processing and extracting geolocation information based on a recorded user dataset
- Using Python, Exploratory data analysis, and null data handling 
- Based on user IP address, extracting user location information by using geolocation databases 

(2)	Data visualization - User dashboard development
- User location mapping on Tableau to confirm the pattern of user distribution.
- By allocating macroeconomic data from world bank and OECD, analyze users' socio-economic status based on geolocation characteristics
- Developing User dashboard to give current key information including User distribution by region, user ratio per population, economic location of the region, and information related to education infrastructure

3.	Result (Visulization result at https://public.tableau.com/app/profile/lauren8177)
 1)User dash board : Latin America & Caribbean (https://public.tableau.com/views/Qanda_Dashboard_MX/MX_dash?:language=en-US&:display_count=n&:origin=viz_share_link) 
 
 2)User dash board : Mexico (<div class='tableauPlaceholder' id='viz1649745649057' style='position: relative'><noscript><a href='#'><img alt='MX_dash ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Qa&#47;Qanda_Dashboard_MX&#47;MX_dash&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Qanda_Dashboard_MX&#47;MX_dash' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Qa&#47;Qanda_Dashboard_MX&#47;MX_dash&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1649745649057');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1800px';vizElement.style.height='977px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1800px';vizElement.style.height='977px';} else { vizElement.style.width='100%';vizElement.style.height='2227px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>)
 3)Correlation board between user and socio economic status factors :


