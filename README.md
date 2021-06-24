<svg xmlns="http://www.w3.org/2000/svg" width="350" height="190" viewBox="0 0 350 190" fill="none">
        <style>
          .header {
            font: 600 18px 'Segoe UI', Ubuntu, Sans-Serif;
            fill: #ff6e96;
            animation: fadeInAnimation 0.8s ease-in-out forwards;
          }
          
    .lang-name { font: 400 11px 'Segoe UI', Ubuntu, Sans-Serif; fill: #f8f8f2 }
  

          
    /* Animations */
    @keyframes scaleInAnimation {
      from {
        transform: translate(-5px, 5px) scale(0);
      }
      to {
        transform: translate(-5px, 5px) scale(1);
      }
    }
    @keyframes fadeInAnimation {
      from {
        opacity: 0;
      }
      to {
        opacity: 1;
      }
    }
  
          * { animation-duration: 0s !important; animation-delay: 0s !important; }
        </style>

        

        <rect data-testid="card-bg" x="0.5" y="0.5" rx="4.5" height="99%" stroke="#e4e2e2" width="349" fill="#282a36" stroke-opacity="1"/>

        
      <g data-testid="card-title" transform="translate(25, 35)">
        <g transform="translate(0, 0)">
      <text x="0" y="0" class="header" data-testid="header">Most Used Languages</text>
    </g>
      </g>
    

        <g data-testid="main-card-body" transform="translate(0, 55)">
          
    <svg data-testid="lang-items" x="25">
      
      <mask id="rect-mask">
        <rect x="0" y="0" width="300" height="8" fill="white" rx="5"/>
      </mask>
      
          <rect mask="url(#rect-mask)" data-testid="lang-progress" x="0" y="0" width="92.49" height="8" fill="#2b7489"/>
        
          <rect mask="url(#rect-mask)" data-testid="lang-progress" x="92.49" y="0" width="67.59" height="8" fill="#563d7c"/>
        
          <rect mask="url(#rect-mask)" data-testid="lang-progress" x="160.07999999999998" y="0" width="39.58" height="8" fill="#f1e05a"/>
        
          <rect mask="url(#rect-mask)" data-testid="lang-progress" x="199.65999999999997" y="0" width="36.19" height="8" fill="#178600"/>
        
          <rect mask="url(#rect-mask)" data-testid="lang-progress" x="235.84999999999997" y="0" width="35.90" height="8" fill="#e34c26"/>
        
          <rect mask="url(#rect-mask)" data-testid="lang-progress" x="271.74999999999994" y="0" width="26.33" height="8" fill="#3572A5"/>
        
          <rect mask="url(#rect-mask)" data-testid="lang-progress" x="298.0799999999999" y="0" width="11.71" height="8" fill="#858585"/>
        
          <rect mask="url(#rect-mask)" data-testid="lang-progress" x="299.7899999999999" y="0" width="10.21" height="8" fill="#355570"/>
        
      
    <g transform="translate(0, 25)">
      <circle cx="5" cy="6" r="5" fill="#2b7489"/>
      <text data-testid="lang-name" x="15" y="10" class="lang-name">
        TypeScript 30.83%
      </text>
    </g>
  
    <g transform="translate(150, 25)">
      <circle cx="5" cy="6" r="5" fill="#563d7c"/>
      <text data-testid="lang-name" x="15" y="10" class="lang-name">
        CSS 22.53%
      </text>
    </g>
  
    <g transform="translate(0, 50)">
      <circle cx="5" cy="6" r="5" fill="#f1e05a"/>
      <text data-testid="lang-name" x="15" y="10" class="lang-name">
        JavaScript 13.19%
      </text>
    </g>
  
    <g transform="translate(150, 50)">
      <circle cx="5" cy="6" r="5" fill="#178600"/>
      <text data-testid="lang-name" x="15" y="10" class="lang-name">
        C# 12.06%
      </text>
    </g>
  
    <g transform="translate(0, 75)">
      <circle cx="5" cy="6" r="5" fill="#e34c26"/>
      <text data-testid="lang-name" x="15" y="10" class="lang-name">
        HTML 11.97%
      </text>
    </g>
  
    <g transform="translate(150, 75)">
      <circle cx="5" cy="6" r="5" fill="#3572A5"/>
      <text data-testid="lang-name" x="15" y="10" class="lang-name">
        Python 8.78%
      </text>
    </g>
  
    <g transform="translate(0, 100)">
      <circle cx="5" cy="6" r="5" fill="#858585"/>
      <text data-testid="lang-name" x="15" y="10" class="lang-name">
        GAP 0.57%
      </text>
    </g>
  
    <g transform="translate(150, 100)">
      <circle cx="5" cy="6" r="5" fill="#355570"/>
      <text data-testid="lang-name" x="15" y="10" class="lang-name">
        GDScript 0.07%
      </text>
    </g>
  
    
    </svg>
  
        </g>
      </svg>
