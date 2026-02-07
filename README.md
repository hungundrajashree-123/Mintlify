# Mintlify
 I tried to recreate Mintlify Website.
 I recreated Top Navigation Bar,Hero section,Row of company logos,UI preview,Case studies,cta buttons,and footer with multi coloumn links and company information.


Here,I have given my html file which i tried to create for Mintlify website.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mintlify</title>
    <link rel="stylesheet"href="style mintlify.css">
</head>
<body>
    <nav class="navbar">
        <!--Left:Logo-->
        <div class="nav-left">
            <img src="https://cdn.brandfetch.io/idUnVg8Dcf/theme/dark/logo.svg?c=1bxid64Mup7aczewSAYMX&t=1736768245431"alt="logo" class="logo">
  
        </div>
        <!--Center: links-->
        <ul class="nav-center">
            <li><a href="#">Resourses</a></li>
            <li><a href="#">Documentation</a></li>
            <li><a href="#">Customers</a></li>
            <li><a href="#">Blog</a></li>
            <li><a href="#">Pricing</a></li>
        </ul>
        <!--Right: Buttons-->
        <div class="nav-right">
            <a href="#"class="btn-outline">Conatct sales</a>
            <a href="#"class="btn-primary">Start for free</a>
        </div>
    </nav>
    <section class="hero">
    <!--Hero section(background goes here)-->
    <div class="hero-badge">
    <span class="badge-new">NEW</span>
    <span class="badge-text">Self-updating docs with agent suggestions</span>   
    <span class="badge-arrow">&rsaquo;</span>
    </div>
    <h1>The Intelligent Knowledge Platform</h1>
    <p>Helping teams create and maintain worls-class documentation built for humans and AI.</p>
</section>

<div class="docs-container">
    <!--Left Sidebar-->
    <aside class="sidebar">
        <div class="sidebar-brand>mintlify"</div>
        <ul class="sidebar-menu">
            <li class="active">Quickstart</li>
            <li>Ask Assistant</li>
            <li>Global Settings</li>
            <li>AI Optimization</li>
            <li>Components</li>
            <li>Themes</li>
            <!--Faded / disabled items-->
            <li class="disabled">Navigation</li>
            <li class="disabled">Versioning</li>
            <li class="disabled"> Custom Domain</li>
            <li class="disabled">Web Editor</li>
            <li class="disabled">Development</li>
            <li class="disabled">Markdown Syntax</li>
        </ul>
    </aside>
    <!--Main Content-->
    <main class="docs-main">
        <!--Top Tabs-->
        <div class="docs-tabs">
            <a class="tab active"href="#">Guides</a>
            <a class="tab" href="#">API Reference</a>
             <a class="tab" href="#">Changelog</a>
    </div>
    <div class="docs-header">
        <h1>Quickstart Guide</h1>
        <p>Start building intelligent documentation in under five minutes</p>
    </div>
    <div class="docs-cards">
        <div class="card">
            <h3>Quickstart</h3>
            <p>Deploy your first docs site in minutes.</p>
     </div>
         <div class="card">
            <h3>Installation</h3>
            <p>Install the CLI to preview and develop docs locally.</p>
         </div>
         <div class="card">
            <h3>Web Editor</h3>
             <p>Edit and manage content directly in the browser.</p>
         </div>
         <div class="card">
            <h3>Components</h3>
            <p>Build beautiful docs using ready-to-use copmponents.</p>
         </div>
    
        </div>
    </main>
<!--Right Sidebar-->
<aside class="rightbar">
    <h4>On this page</h4>
    <ul>
        <li class="active">Introduction</li>
        <li> Getting Started</li>
        <li>AI Optimization</li>
        <li>Themes</li>

    </ul>
</aside>
</div>
<section class="trusted section">
    <div class="logo-grid">
        <img src="https://cdn.brandfetch.io/idmJWF3N06/theme/dark/logo.svg?c=1bxid64Mup7aczewSAYMX&t=1721803183485"alt="Anthropic">
        <img src="https://cdn.brandfetch.io/idwDWo4ONQ/theme/dark/logo.svg?c=1bxid64Mup7aczewSAYMX&t=1667593749615alt"alt="Coinbase">
        <img src="https://cdn.brandfetch.io/idchmboHEZ/theme/dark/logo.svg?c=1bxid64Mup7aczewSAYMX&t=1727706672983"alt="Microsoft">
        <img src="https://cdn.brandfetch.io/idNdawywEZ/theme/dark/idM0TjLEnG.svg?c=1bxid64Mup7aczewSAYMX&t=1754453412931"alt="Perplexity">
        <img src="https://cdn.brandfetch.io/idRt0LuzRf/theme/dark/logo.svg?c=1bxid64Mup7aczewSAYMX&t=1761193704935"alt="Hubspot">
        <img src="https://cdn.brandfetch.io/idS5WhqBbM/theme/dark/logo.svg?c=1bxid64Mup7aczewSAYMX&t=1692089092800"alt="X">
        <img src="https://cdn.brandfetch.io/id-Wd4a4TS/theme/dark/id31tBizMM.svg?c=1bxid64Mup7aczewSAYMX&t=1727787879793"alt="Paypal">
        <img src="https://cdn.brandfetch.io/idH9OjyiUq/theme/dark/logo.svg?c=1bxid64Mup7aczewSAYMX&t=1748239860810"alt-"Lovable">
        
    </div>
</section>
<!--Built for intelligence section-->
<section class="intelligence">
    <h2>Built for the intelligence age</h2>
    <p>Integrate AI into every part of your docs lifecycle.Woven into how your
         knowledge is written,maintained,and understood by both users and LLMS.</p>

<!--2 column content-->
<div class="intelligence-grid">
    <!--Left column-->
    <div class="intellingence-card">
        <span class="tag">LLMS,TXT & MCP</span>
        <h3>Built for both people and AI</h3>
        <p>Ensure your product shows up in the AI workflows users already rely on.
            We support llms.txt,MCP,and whatever comes next.
        </p>
        <!--visual-->
        <div class="visual">
            <img src="https://private-user-images.githubusercontent.com/257071786/546309400-31f186c2-71a2-43c9-8867-7dabec6880c3.jpeg?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NzAzOTY2NDcsIm5iZiI6MTc3MDM5NjM0NywicGF0aCI6Ii8yNTcwNzE3ODYvNTQ2MzA5NDAwLTMxZjE4NmMyLTcxYTItNDNjOS04ODY3LTdkYWJlYzY4ODBjMy5qcGVnP1gtQW16LUFsZ29yaXRobT1BV1M0LUhNQUMtU0hBMjU2JlgtQW16LUNyZWRlbnRpYWw9QUtJQVZDT0RZTFNBNTNQUUs0WkElMkYyMDI2MDIwNiUyRnVzLWVhc3QtMSUyRnMzJTJGYXdzNF9yZXF1ZXN0JlgtQW16LURhdGU9MjAyNjAyMDZUMTY0NTQ3WiZYLUFtei1FeHBpcmVzPTMwMCZYLUFtei1TaWduYXR1cmU9MmYwNGRkZjQwNTE3ZGM0NjUyYTA1YjI2ZGVjNWM4NTYzMzViNDEwZWI4M2UwYTRmZGQ2Y2VkN2I2NGI5NGRlNSZYLUFtei1TaWduZWRIZWFkZXJzPWhvc3QifQ.WCQI4dwYqJisprek6_GASY9f-E9GVEObfFn9UVBS1Zk"alt="visual">
        </div>
    </div>
     <!--Right column-->
     <div class="intellingence-card">
        <span class="tag">AGENT</span>
        <h3>Self-updating knowledge management</h3>
        <p> Draft,edit,and maintain 
            content with a context-aware agent.
            Move faster and more consistently
        without the documentation debt.</p>
        <!--visual-->
        <div class="visual">
            <img src="https://private-user-images.githubusercontent.com/257071786/546309321-438c794a-8512-4e8e-a187-74bc74a7b698.jpeg?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NzAzOTY2NDcsIm5iZiI6MTc3MDM5NjM0NywicGF0aCI6Ii8yNTcwNzE3ODYvNTQ2MzA5MzIxLTQzOGM3OTRhLTg1MTItNGU4ZS1hMTg3LTc0YmM3NGE3YjY5OC5qcGVnP1gtQW16LUFsZ29yaXRobT1BV1M0LUhNQUMtU0hBMjU2JlgtQW16LUNyZWRlbnRpYWw9QUtJQVZDT0RZTFNBNTNQUUs0WkElMkYyMDI2MDIwNiUyRnVzLWVhc3QtMSUyRnMzJTJGYXdzNF9yZXF1ZXN0JlgtQW16LURhdGU9MjAyNjAyMDZUMTY0NTQ3WiZYLUFtei1FeHBpcmVzPTMwMCZYLUFtei1TaWduYXR1cmU9ZmU5YWRkYThkN2RkYTI2ZDY0MjJjMmFiYzA3NTYxMDM4OTUyNGFhOTNkZTczZjZkYTQ3MzkxODEwZTk0YTM5OCZYLUFtei1TaWduZWRIZWFkZXJzPWhvc3QifQ.tLt2LuYifJ8QZy6cR08TBngmxIHhWCR7J-iwmoWR0aI"alt="visual">
        </div>
     </div>
</div>
</section>


<section class="enterprise">
  <div class="enterprise-wrap">

    <!-- Top row -->
    <div class="enterprise-top">
      <div class="enterprise-text">
        <p class="eyebrow">ENTERPRISE REINVENTION</p>
        <h2>Bring intelligence to enterprise knowledge</h2>
             <p class="subtext">
          Modernize without the rebuild with enterprise-grade professional service & security.
        </p>
      </div>
      <a href="#" class="enterprise-btn">Explore for enterprise</a>
    </div>

    <!-- Features row -->
    <div class="enterprise-features">
      <div class="feature-item">
        <h4>Build with partnership</h4>
        <p>
          Direct, white-glove access to our documentation experts. Dedicated migration support
          and guidance tailored to your setup, and elevated support SLAs.
        </p>
      </div>

      <div class="feature-item">
        <h4>Compliance and access control</h4>
        <p>
          Compliant with SOC 2, and in the process for ISO27001 and GDPR compliance to meet your
           internal and external data requirements. Secure access and provisioning with SAML-based SSO.
        </p>
      </div>
    </div>

    <!-- Big image card -->
    <div class="customer-card">
      <img src="https://www.mintlify.com/enterprise/anthropic.svg"alt="anthropic">
      <div class="card-overlay">
        <p class="tag">CUSTOMER STORY</p>
        <h3>See how Anthropic accelerates AI development with Mintlify</h3>
          <span class="read">Read story →</span>

        <div class="card-stats">
          <div>
            <strong>2M+</strong>
            <p>Monthly active developers</p>
          </div>
          <div>
            <strong>3+</strong>
            <p>Products serviced: Claude API, MCP, and Claude Code</p>
          </div>
        </div>
       </div>
       </div>
 
    <!-- Logo row -->
    <div class="logo-row">
      <img src="https://cdn.brandfetch.io/idmJWF3N06/theme/dark/logo.svg?c=1bxid64Mup7aczewSAYMX&t=1721803183485"alt="Anthropic">
      <img src="https://cdn.brandfetch.io/idwDWo4ONQ/theme/dark/logo.svg?c=1bxid64Mup7aczewSAYMX&t=1667593749615"alt="Coinbase">
    
      <img src="https://cdn.brandfetch.io/idRt0LuzRf/theme/dark/logo.svg?c=1bxid64Mup7aczewSAYMX&t=1761193704935"alt="Hubspot">
      <img src="https://cdn.brandfetch.io/idNMs_nMA0/theme/dark/logo.svg?c=1bxid64Mup7aczewSAYMX&t=1667563370508"alt="zapier">
    </div>

  </div>
</section>
<section class="customers">
  <p class="small-title">CUSTOMERS</p>
  <h2>Unlock knowledge for any industry</h2>
  <p class="subtitle">
    From frontier AI companies to consumer brands, leaders across industries scale with Mintlify.
  </p>

  <div class="cards-row">
    <div class="card">
      <img src="https://www.mintlify.com/_next/image?url=%2Fcustomers%2Fperplexity.png&w=640&q=75"alt="Perplexity">
      <p>How Perplexity transformed its documentation into an AI-native developer experience.</p>
      <a href="#">Read story →</a>
    </div>

    <div class="card">
      <img src="https://www.mintlify.com/_next/image?url=%2Fcustomers%2Fx.png&w=640&q=75"alt="X">
      <p>How X is using Mintlify to power the developer experience.</p>
      <a href="#">Read story →</a>
    </div>

    <div class="card">
      <img src="https://www.mintlify.com/_next/image?url=%2Fcustomers%2Fkalshi.png&w=640&q=75"alt="Kalshi">
      <p>How Kalshi helps developers discover what's possible faster and ultimately drive broader.</p>
      <a href="#">Read story →</a>
    </div>

    <div class="card">
      <img src="https://www.mintlify.com/_next/image?url=%2Fcustomers%2Fcognition.png&w=640&q=75"alt="Cognition">
      <p>How Cognition scaled their documentation to mirror their product ethos.</p>
      <a href="#">Read story →</a>
    </div>
    <div class="card">
      <img src="https://www.mintlify.com/_next/image?url=%2Fcustomers%2Ftogetherai.png&w=640&q=75"alt="togetherAI">
      <p>How Together AI scaled their documentation into a developer experience that mirrors their ethos</p>
      <a href="#">Read story →</a>
</div>
<div class="card">
      <img src="https://www.mintlify.com/_next/image?url=%2Fcustomers%2Flaravel.png&w=640&q=75"alt="togetherAI">
      <p>How Together AI scaled their documentation into a developer experience that mirrors their ethos</p>
      <a href="#">Read story →</a>
</div>

<!--Slider Buttons-->
<div class="slider-buttons"
<button class="nav-btn">&larr;</button>
<button class="nav-btn">&rarr;</button>
  </div>

  </div>
</section>
<section class="cta">
  <h2>Make documentation<br>your winning advantage</h2>
  <p class="cta-sub">
    Join the leaders of tomorrow to future proof your documentation today.
   </p>

  <div class="cta-buttons">
    <a href="#" class="btn primary">Get started for free</a>
    <a href="#" class="btn ghost">Get a demo</a>
  </div>
</section>
<footer class="site-footer">
  <div class="footer-top">
    <div class="footer-brand">
      <img src="https://cdn.brandfetch.io/idUnVg8Dcf/theme/dark/logo.svg?c=1bxid64Mup7aczewSAYMX&t=1736768245431"alt="Mintlify" class="footer-logo">
    </div>

    <div class="footer-cols">
      <div class="footer-col">
        <h4>Explore</h4>
        <a href="#">Startups</a>
        <a href="#">Enterprise</a>
        <a href="#">Switch</a>
        <a href="#">OSS Program</a>
      </div>

      <div class="footer-col">
        <h4>Resources</h4>
        <a href="#">Customers</a>
        <a href="#">Blog</a>
        <a href="#">Pricing</a>
        <a href="#">Guides</a>
        <a href="#">Feature Requests</a>
      </div>

      <div class="footer-col">
        <h4>Documentation</h4>
        <a href="#">Getting Started</a>
        <a href="#">API Reference</a>
        <a href="#">Components</a>
        <a href="#">Changelog</a>
      </div>

      <div class="footer-col">
        <h4>Company</h4>
        <a href="#">Careers</a>
        <a href="#">Wall of Love</a>
      </div>

      <div class="footer-col">
        <h4>Legal</h4>
        <a href="#">Privacy Policy</a>
        <a href="#">Responsible Disclosure</a>
        <a href="#">Terms of Service</a>
        <a href="#">Security</a>
        <a href="#">DSR/DSAR</a>
      </div>
    </div>
  </div>

  <div class="footer-bottom">
    <p>Backed by Enterprise-Grade Security</p>
    <p> &copy; 2026 Mintlify, Inc.</p>
  </div>
</footer>




[mintlify.html](https://github.com/user-attachments/files/25142961/mintlify.html)

 
