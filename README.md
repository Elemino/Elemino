<p align="center">
  <svg width="600" height="200" viewBox="0 0 600 200" xmlns="http://w3.org">
    <defs>
      <filter id="distort">
        <feTurbulence type="fractalNoise" baseFrequency="0.01 0.1" numOctaves="2" result="noise">
          <animate attributeName="baseFrequency" values="0.01 0.1;0.02 0.2;0.01 0.1" dur="3s" repeatCount="indefinite" />
        </feTurbulence>
        <feDisplacementMap in="SourceGraphic" in2="noise" scale="15" />
      </filter>
      
      <linearGradient id="grad" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" style="stop-color:#00d2ff;stop-opacity:1" />
        <stop offset="100%" style="stop-color:#3a7bd5;stop-opacity:1" />
      </linearGradient>
    </defs>
    
    <!-- Shadow Layer for 3D depth -->
    <text x="50%" y="50%" dy=".35em" text-anchor="middle" font-family="sans-serif" font-weight="900" font-size="80" fill="#111" filter="url(#distort)" opacity="0.5" transform="translate(4, 4)">
      Elemino
    </text>
    
    <!-- Main Text -->
    <text x="50%" y="50%" dy=".35em" text-anchor="middle" font-family="sans-serif" font-weight="900" font-size="80" fill="url(#grad)" filter="url(#distort)">
      Elemino
    </text>
  </svg>
</p>



### Greetings

-  I’m currently working on building things people will want to use. 
-  Currenly 3D modeling, mechanical engineering, and more. 
-  I’m looking to collaborate on anything Web 3.0, AR, Autonomous Vehicles, and IOT.


