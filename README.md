<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Effortlessly transform your HTML documents into XML format with our user-friendly converter tool.">
  <meta name="keywords" content="HTML, XML, Converter, Code, HTML to XML conversion, HTML to XML converter tool, Convert HTML to XML, Transform HTML into XML, HTML parsing, XML encoding, Web development utilities, Data conversion, Markup language conversion, Document format conversion, Code conversion, Structured data conversion, Web development tools, XML generation, Data interchange, XML formatting, HTML document processing, Markup language translation, Online HTML to XML converter, HTML to XML conversion software">
  <link rel="icon" type="image/png" href="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEi4494uMUgDzmugNbncDv4Sf1TRkK83btSnRSaSliAUWYrKNqTvcIYcl_pAFq4J8KHF5F5je4VsgT0a0AtW1WUXemSGjCLPywPwV3WlnDJlUsoJYdr6ghkTD5Zw0ag2fwQdn6Ub266pSrnDH7qQU_kf0UW-kWqtQzKVooZOhBOsju3wezBtq2coTMb4JAk/w320-h320/web-development.png">
  <title>HTML to XML Converter</title>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap" rel="stylesheet">
  <style>
    /* Add your custom styles here */
    body {
      background-color: #f4f8fa;
      color: #333;
      font-family: 'Poppins', sans-serif;
    }

    .logo {
      display: flex;
      align-items: center;
    }

    .logo img {
      height: 40px;
      margin-right: 10px;
    }
    .bg-light {
    background-color: #F8F8FA!important;
    border-radius: 10px;
}

    header {
      background-color: #99FE84;
      padding: 20px;
      margin-bottom: 0;
    }

    .navbar-brand {
      color: #000;
      font-size: 24px;
    }

    .navbar-toggler {
      border-color: transparent;
      color: #000;
      font-size: 28px;
    }

    .navbar-toggler:hover, .navbar-toggler:focus {
      border-color: transparent;
      color: #000;
    }

    .navbar-toggler-icon {
      background-color: #99FE84;
      border-radius: 5px;
    }

    .introduction {
      text-align: center;
      padding: 40px 0;
      background-color: #f8f9fa;
    }

    .tool-name {
      font-size: 32px;
      margin-bottom: 20px;
      background-color: #99FE84;
      padding: 10px 20px;
      display: inline-block;
      border-radius: 5px;
    }

    .tool-description {
      font-size: 18px;
      margin-bottom: 10px;
    }

    main {
      padding: 20px;
    }

    textarea {
      width: 100%;
      margin-bottom: 10px;
    }

    #convertBtn {
      display: block;
      margin-top: 10px;
      background-color: #99FE84;
      border-color: #99FE84;
      color: #333;
      padding: 8px 16px;
      border-radius: 5px;
      font-size: 18px;
      width: 100%;
    }

    #xmlOutput {
      height: 200px;
    }

    footer {
      background-color: #99FE84;
      padding: 20px;
      text-align: center;
      color: #333;
    }

    footer ul {
      list-style: none;
      padding: 0;
      margin-bottom: 20px;
    }

    footer ul li {
      display: inline-block;
      margin-right: 10px;
    }

    footer ul li a {
      text-decoration: none;
      color: #333;
    }

    /* Popup styles */
    .popup {
      display: none;
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background-color: rgba(255, 255, 255, 0.9);
      z-index: 9999;
      text-align: center;
      padding-top: 100px;
      overflow-y: auto;
    }

    .popup-content {
      background-color: #f8f9fa;
      padding: 20px;
      margin: 0 auto;
      width: 80%;
      max-width: 600px;
      border-radius: 5px;
      color: #333;
      overflow-y: auto;
    }

    .close-btn {
      position: absolute;
      top: 10px;
      right: 10px;
      color: #333;
      font-size: 20px;
      cursor: pointer;
    }

 

    /* Ads Css COde */
    .ad-wrapper {
  display: flex;
  justify-content: center;
  align-items: center;
  height:100px;
  margin-bottom: 10px;
}

.ad-container {
  width: 100%;
  max-width: 720px;
  height: 90px;
  border: 1px solid #ccc;
  overflow: hidden;
  border-radius: 5px;
}

.ad-link {
  display: block;
  width: 100%;
  height: 100%;
}

.ad-content {
  width: 100%;
  height: 100%;
  background-color: #f8f9fa;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0 10px;
}

.ad-text {
  font-size: 18px;
  font-weight: bold;
  color: #333;
}

.ad-button {
  display: block;
    margin-top: 10px;
    background-color: #99FE84;
    border-color: #99FE84;
    color: #333;
    padding: 8px 16px;
    border-radius: 5px;
    font-size: 18px;
}
.btn-primary{
  display: block;
    margin-top: 10px;
    background-color: #99FE84;
    border-color: #99FE84;
    color: #333;
    padding: 8px 16px;
    border-radius: 5px;
    font-size: 18px;
}
.coryright {
    margin-top: 10px;
    background-color: #99FE84;
    border-color: #99FE84;
    color: #333;
    padding: 3px 4px;
    border-radius: 5px;
    font-size: 15px;
    text-decoration: none;
}
#clearBtn,
#copyBtn {
  display: block;
  margin-top: 10px;
  background-color: #99FE84;
  border-color: #99FE84;
  color: #333;
  padding: 8px 16px;
  border-radius: 5px;
  font-size: 18px;
  width: 100%;
}


  </style>
</head>
<body>
  <header>
    <div class="container-fluid">
      <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <a class="navbar-brand" href="#"><img style="width: 45px;" src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEi4494uMUgDzmugNbncDv4Sf1TRkK83btSnRSaSliAUWYrKNqTvcIYcl_pAFq4J8KHF5F5je4VsgT0a0AtW1WUXemSGjCLPywPwV3WlnDJlUsoJYdr6ghkTD5Zw0ag2fwQdn6Ub266pSrnDH7qQU_kf0UW-kWqtQzKVooZOhBOsju3wezBtq2coTMb4JAk/w320-h320/web-development.png" alt="Logo"></a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav ml-auto">
            <li class="nav-item"><a style="color: #000;" class="nav-link" href="/">🏠 Home</a></li>
            <li class="nav-item"><a style="color: #000;"  href="#aboutPopup" class="nav-link popup-link" data-popup="#aboutPopup">💡 About Us</a></li>
            <li class="nav-item"><a style="color: #000;" href="#contactPopup" class="nav-link popup-link" data-popup="#contactPopup">📞 Contact Us</a></li>
            <li class="nav-item"><a style="color: #000;" href="#privacypolicypopup" class="nav-link popup-link" data-popup="#pagesPopup">📚 Privacy Policy</a></li>
            <li class="nav-item"><a style="color: #000;" href="#disclaimerpopup" class="nav-link popup-link" data-popup="#toolsPopup">🛠️ Disclaimer</a></li>
          </ul>
        </div>
      </nav>
    </div>
  </header>

  <main>
    <div class="container">
      <div class="introduction">
        <h1 class="tool-name">HTML to XML Converter</h1>
        <p class="tool-description">🌐 Explore our HTML to XML Converter By Afzaal Blogger 🔥</p>
        <!-- Ads Place Start -->
        <div class="ad-wrapper">
          <div class="ad-container">
            <a href="#" class="ad-link">
              <div class="ad-content">
                <div class="ad-text">Your Ad Here</div>
                <button class="ad-button">Click Here</button>
              </div>
            </a>
          </div>
        </div>        
        <!-- Ads Place End-->  
        <p class="tool-description">🔁 Easily switch your HTML documents to XML format with our user-friendly tool. Whether you're a coding enthusiast, a data wizard, or just need to convert your HTML files, our solution is here to streamline the entire transformation process. 🚀       </p>
      </div>

      <div class="row">
        <div class="col-md-8 offset-md-2">
          <textarea id="htmlInput" rows="10" class="form-control" placeholder="Enter your HTML code here"></textarea>
          <center><button id="convertBtn" class="btn btn-primary">Convert to XML</button></center><br>
          <!-- Ads Place Start -->
        <div class="ad-wrapper">
          <div class="ad-container">
            <a href="#" class="ad-link">
              <div class="ad-content">
                <div class="ad-text">Your Ad Here</div>
                <button class="ad-button">Click Here</button>
              </div>
            </a>
          </div>
        </div>        
        <!-- Ads Place End-->  
        <br>
          <textarea id="xmlOutput" rows="10" class="form-control" readonly></textarea>
          <center><a id="downloadBtn" class="btn btn-primary" href="#" download="converted.xml">Save Your XML Code</a></center>
          <button id="clearBtn" class="btn btn-primary">Clear XML Code</button>
          <button id="copyBtn" class="btn btn-primary">Copy to Clipboard</button>
        </div>
      </div>
    </div>
    <br>
    <!-- Ads Place Start -->
    <div class="ad-wrapper">
      <div class="ad-container">
        <a href="#" class="ad-link">
          <div class="ad-content">
            <div class="ad-text">Your Ad Here</div>
            <button class="ad-button">Click Here</button>
          </div>
        </a>
      </div>
    </div>        
    <!-- Ads Place End-->  
    <br>
    <article class="container">
      <center><h2>About HTML to XML Converter</h2></center>
      <h5>Step 1: Input your HTML code 📥</h5>
      <p>Start by copying your HTML code and pasting it into the designated text area.</p>
    
      <h5>Step 2: Convert to XML ✨</h5>
      <p>Click the "Convert" button to initiate the conversion process.</p>
      <p>Our converter will analyze your HTML code and transform it into valid XML format.</p>
    
      <h5>Step 3: Download your XML file 📤</h5>
      <p>Once the conversion is complete, a download link will be provided.</p>
      <p>Simply click on the link to download your XML file to your device.</p>
    
      <h5>Step 4: Edit and reconvert 🔄</h5>
      <p>If needed, you can make modifications to your HTML code and reconvert it to XML.</p>
      <p>Repeat the conversion process by pasting your updated HTML code and clicking the "Convert" button again.</p>
    
      <h5>Step 5: Secure and reliable 🛡️</h5>
      <p>Your privacy and data security are our top priorities.</p>
      <p>Rest assured that your HTML code is handled securely on our reliable server infrastructure.</p>
    
      <h5>Step 6: Cross-browser compatibility 🌐</h5>
      <p>Our HTML to XML Converter website works seamlessly across different web browsers.</p>
      <p>Whether you prefer Chrome, Firefox, Safari, or any other popular browser, our website ensures consistent performance.</p>
    
      <h5>Step 7: Free and accessible 🆓</h5>
      <p>Our HTML to XML Converter is completely free to use, without any hidden charges or subscriptions.</p>
      <p>Access our converter from anywhere with an internet connection, making it easily accessible.</p>
    
      <h5>Step 8: User-friendly interface 🌟</h5>
      <p>Navigate through our website effortlessly with its clean and intuitive interface.</p>
      <p>Our converter is designed to be beginner-friendly, regardless of your technical expertise.</p>
    
      <h5>Get started now! 🚀</h5>
      <p>Start using our HTML to XML Converter to effortlessly convert your HTML code into XML format.</p>
      <p>Save time, ensure accuracy, and enhance your XML document workflow!</p>
    </article>
    <br>
    <!-- Ads Place Start -->
    <div class="ad-wrapper">
      <div class="ad-container">
        <a href="#" class="ad-link">
          <div class="ad-content">
            <div class="ad-text">Your Ad Here</div>
            <button class="ad-button">Click Here</button>
          </div>
        </a>
      </div>
    </div>        
    <!-- Ads Place End-->  
  </main>

  <footer class="bg-light text-center">
    <div class="container">
      <ul class="list-inline">
        <li class="list-inline-item"><a href="#aboutPopup" class="popup-link" data-popup="#aboutPopup">💡 About Us</a></li>
        <li class="list-inline-item"><a href="#contactPopup" class="popup-link" data-popup="#contactPopup">📞 Contact Us</a></li>
        <li class="list-inline-item"><a href="#pagesPopup" class="popup-link" data-popup="#pagesPopup">📚 Privacy Policy</a></li>
        <li class="list-inline-item"><a href="#toolsPopup" class="popup-link" data-popup="#toolsPopup">🛠️ Disclaimer</a></li>
      </ul>
      <p>Credit by <strong><a class="coryright" href="https://afzaalblogger.com">Afzaal Blogger</a></strong></p>
    </div>
  </footer>

  <!-- Popup Modules -->
  <div id="pagesPopup" class="popup">
    <div class="popup-content">
      <h2>Privacy Policy 📚</h2>
      <h1>Privacy Policy for Html to Xml Converter </h1>

<p>At Html to Xml Converter , accessible from https:converterfix.blogspot.com, one of our main priorities is the privacy of our visitors. This Privacy Policy document contains types of information that is collected and recorded by Html to Xml Converter  and how we use it.</p>

<p>If you have additional questions or require more information about our Privacy Policy, do not hesitate to contact us.</p>

<p>This Privacy Policy applies only to our online activities and is valid for visitors to our website with regards to the information that they shared and/or collect in Html to Xml Converter . This policy is not applicable to any information collected offline or via channels other than this website.</p>

<h2>Consent</h2>

<p>By using our website, you hereby consent to our Privacy Policy and agree to its terms.</p>

<h2>Information we collect</h2>

<p>The personal information that you are asked to provide, and the reasons why you are asked to provide it, will be made clear to you at the point we ask you to provide your personal information.</p>
<p>If you contact us directly, we may receive additional information about you such as your name, email address, phone number, the contents of the message and/or attachments you may send us, and any other information you may choose to provide.</p>
<p>When you register for an Account, we may ask for your contact information, including items such as name, company name, address, email address, and telephone number.</p>

<h2>How we use your information</h2>

<p>We use the information we collect in various ways, including to:</p>

<ul>
<li>Provide, operate, and maintain our website</li>
<li>Improve, personalize, and expand our website</li>
<li>Understand and analyze how you use our website</li>
<li>Develop new products, services, features, and functionality</li>
<li>Communicate with you, either directly or through one of our partners, including for customer service, to provide you with updates and other information relating to the website, and for marketing and promotional purposes</li>
<li>Send you emails</li>
<li>Find and prevent fraud</li>
</ul>

<h2>Log Files</h2>

<p>Html to Xml Converter  follows a standard procedure of using log files. These files log visitors when they visit websites. All hosting companies do this and a part of hosting services' analytics. The information collected by log files include internet protocol (IP) addresses, browser type, Internet Service Provider (ISP), date and time stamp, referring/exit pages, and possibly the number of clicks. These are not linked to any information that is personally identifiable. The purpose of the information is for analyzing trends, administering the site, tracking users' movement on the website, and gathering demographic information.</p>

<h2>Cookies and Web Beacons</h2>

<p>Like any other website, Html to Xml Converter  uses "cookies". These cookies are used to store information including visitors' preferences, and the pages on the website that the visitor accessed or visited. The information is used to optimize the users' experience by customizing our web page content based on visitors' browser type and/or other information.</p>

<h2>Google DoubleClick DART Cookie</h2>

<p>Google is one of a third-party vendor on our site. It also uses cookies, known as DART cookies, to serve ads to our site visitors based upon their visit to www.website.com and other sites on the internet. However, visitors may choose to decline the use of DART cookies by visiting the Google ad and content network Privacy Policy at the following URL – <a href="https://policies.google.com/technologies/ads">https://policies.google.com/technologies/ads</a></p>

<h2>Our Advertising Partners</h2>

<p>Some of advertisers on our site may use cookies and web beacons. Our advertising partners are listed below. Each of our advertising partners has their own Privacy Policy for their policies on user data. For easier access, we hyperlinked to their Privacy Policies below.</p>

<ul>
    <li>
        <p>Google</p>
        <p><a href="https://policies.google.com/technologies/ads">https://policies.google.com/technologies/ads</a></p>
    </li>
</ul>

<h2>Advertising Partners Privacy Policies</h2>

<P>You may consult this list to find the Privacy Policy for each of the advertising partners of Html to Xml Converter .</p>

<p>Third-party ad servers or ad networks uses technologies like cookies, JavaScript, or Web Beacons that are used in their respective advertisements and links that appear on Html to Xml Converter , which are sent directly to users' browser. They automatically receive your IP address when this occurs. These technologies are used to measure the effectiveness of their advertising campaigns and/or to personalize the advertising content that you see on websites that you visit.</p>

<p>Note that Html to Xml Converter  has no access to or control over these cookies that are used by third-party advertisers.</p>

<h2>Third Party Privacy Policies</h2>

<p>Html to Xml Converter 's Privacy Policy does not apply to other advertisers or websites. Thus, we are advising you to consult the respective Privacy Policies of these third-party ad servers for more detailed information. It may include their practices and instructions about how to opt-out of certain options. </p>

<p>You can choose to disable cookies through your individual browser options. To know more detailed information about cookie management with specific web browsers, it can be found at the browsers' respective websites.</p>

<h2>CCPA Privacy Rights (Do Not Sell My Personal Information)</h2>

<p>Under the CCPA, among other rights, California consumers have the right to:</p>
<p>Request that a business that collects a consumer's personal data disclose the categories and specific pieces of personal data that a business has collected about consumers.</p>
<p>Request that a business delete any personal data about the consumer that a business has collected.</p>
<p>Request that a business that sells a consumer's personal data, not sell the consumer's personal data.</p>
<p>If you make a request, we have one month to respond to you. If you would like to exercise any of these rights, please contact us.</p>

<h2>GDPR Data Protection Rights</h2>

<p>We would like to make sure you are fully aware of all of your data protection rights. Every user is entitled to the following:</p>
<p>The right to access – You have the right to request copies of your personal data. We may charge you a small fee for this service.</p>
<p>The right to rectification – You have the right to request that we correct any information you believe is inaccurate. You also have the right to request that we complete the information you believe is incomplete.</p>
<p>The right to erasure – You have the right to request that we erase your personal data, under certain conditions.</p>
<p>The right to restrict processing – You have the right to request that we restrict the processing of your personal data, under certain conditions.</p>
<p>The right to object to processing – You have the right to object to our processing of your personal data, under certain conditions.</p>
<p>The right to data portability – You have the right to request that we transfer the data that we have collected to another organization, or directly to you, under certain conditions.</p>
<p>If you make a request, we have one month to respond to you. If you would like to exercise any of these rights, please contact us.</p>

<h2>Children's Information</h2>

<p>Another part of our priority is adding protection for children while using the internet. We encourage parents and guardians to observe, participate in, and/or monitor and guide their online activity.</p>

<p>Html to Xml Converter  does not knowingly collect any Personal Identifiable Information from children under the age of 13. If you think that your child provided this kind of information on our website, we strongly encourage you to contact us immediately and we will do our best efforts to promptly remove such information from our records.</p>

<h2>Changes to This Privacy Policy</h2>

<p>We may update our Privacy Policy from time to time. Thus, we advise you to review this page periodically for any changes. We will notify you of any changes by posting the new Privacy Policy on this page. These changes are effective immediately, after they are posted on this page.</p>

<p>Our Privacy Policy was created with the help of the <a href="https://www.termsfeed.com/privacy-policy-generator/">Privacy Policy Generator</a>.</p>

<h2>Contact Us</h2>

<p>If you have any questions or suggestions about our Privacy Policy, do not hesitate to contact us.</p>
      <span class="close-btn" data-popup="#pagesPopup">&times;</span>
    </div>
  </div>

  <div id="aboutPopup" class="popup">
    <div class="popup-content">
      <h2>About Us 🌟</h2>
      <p>Welcome to the HTML to XML Converter, your reliable tool for transforming HTML code into XML format! 📄➡️📃</p>
      <h5>Our Mission 🎯</h5>
      <p>At HTML to XML Converter, our mission is to simplify the conversion process and provide a seamless experience for developers, content creators, and anyone working with XML documents. ✨🚀</p>
    
      <h5>Why Choose Us? 🤔</h5>
      
          <h5>Effectiveness ⏱️</h5>
          <p>Our converter ensures fast and accurate conversion of your HTML code into valid XML format. Save valuable time and effort in manually performing the conversion. 💪</p>

          <h5>User-Friendly Interface 🖥️</h5>
          <p>We emphasize user-friendliness, offering a sleek and intuitive interface for your convenience. Whether you're an experienced developer or a beginner, our converter is crafted to be effortlessly accessible. 👩‍💻👨‍💻</p>

          <h5>Privacy and Security 🔒</h5>
          <p>We value the privacy and security of your data. When you use our converter, rest assured that your HTML code is handled securely and kept confidential. 🛡️🔐</p>

          <h5>Cross-Browser Compatibility 🌍</h5>
          <p>Our converter works seamlessly across different web browsers, ensuring a consistent experience regardless of your preferred browser. 🌐✨</p>

          <h5>Free and Accessible 🆓🌈</h5>
          <p>Our commitment is to offer accessible tools to the community. Our HTML to XML Converter is entirely free to use, with no concealed fees or restrictions. 🎁🌟</p>
          <h5>Dependable Assistance 🤝🔧</h5>
          <p>Should you encounter any difficulties or have inquiries while utilizing our converter, our committed support team stands ready to assist you. We are committed to delivering prompt and valuable support to guarantee a seamless experience. 📞💡</p>
      <h4>Start Converting Now! 🚀</h4>
      <p>Harness the Power of Our HTML to XML Converter Today and Streamline Your XML Document Workflow. Discover the Efficiency, Ease, and Precision of Our Conversion Tool. ✨💼</p>
      <p>Thank you for choosing our HTML to XML Converter! 🙏😊</p>
      <p>Regards From Afzaal Blogger</p>
      <br>
      <br>
      <span class="close-btn" data-popup="#aboutPopup">&times;</span>
    </div>
  </div>

  <div id="contactPopup" class="popup">
    <div class="popup-content">
      <h2>Contact Us 📞</h2>
      <p>📬 Have Questions, Feedback, or Need Assistance? 🤝

Please don't hesitate to reach out to us. We're here to assist! 💬</p>
  <h5>Email Us 📧</h5>
  <p>You can reach us via email 📞 at <a href="mailto:afzaalblogger@gmail.com">AfzaalBlogger@gmail.com</a>. We'll respond to you at the earliest opportunity.</p>
  <h5>Follow Us on Social Media 🌐</h5>
  <p>Stay updated with the latest news, updates, and tips by following us on social media:</p>
  <ul>
    Website: <a href="https://afzaalblogger.com.com/your_handle">Afzaal Blogger</a><br>
    Facebook: <a href="https://web.facebook.com/profile.php?id=100094448475066">Afzaal Blogger</a><br>
    Youtube: <a href="https://www.youtube.com/channel/UCs81P-ulIFiWstzdoc5IV1Q">Afzaal Blogger</a><br>
    Medium: <a href="https://medium.com/@Afzaalblogger">@AfzaalBlogger</a><br>
    Pinterest: <a href="https://www.pinterest.com/afzaalblogger/">@AfzaalBlogger</a><br>
  </ul>
  <h5>Business Inquiries 💼</h5>
  <p>If you have any business inquiries or partnership opportunities, please email us at <a href="mailto:AfzaalBlogger@gmail.com">AfzaalBlogger@gmail.com</a>. We look forward to hearing from you!</p>
  <h5>Thank You For Visiting our Website! 😊</h5>
  <p>🙌 Thank you for choosing our HTML to XML Converter and for getting in touch with us! 🌟 We value your support and feedback! 🚀</p>
  <br>
  <br>
      <span class="close-btn" data-popup="#contactPopup">&times;</span>
    </div>
  </div>

  <div id="toolsPopup" class="popup">
    <div class="popup-content">
      <h2>Disclaimer 🛠️</h2>
      <h1>Disclaimer for Html to Xml Converter </h1>

<p>If you require any more information or have any questions about our site's disclaimer, please feel free to contact us by email at afzaalblogger@gmail.com. Our Disclaimer was generated with the help of the <a href="https://www.disclaimergenerator.net/">Free Disclaimer Generator</a>.</p>

<h2>Disclaimers for Html to Xml Converter </h2>

<p>All the information on this website - https://converterfix.blogspot.com - is published in good faith and for general information purpose only. Html to Xml Converter  does not make any warranties about the completeness, reliability and accuracy of this information. Any action you take upon the information you find on this website (Html to Xml Converter ), is strictly at your own risk. Html to Xml Converter  will not be liable for any losses and/or damages in connection with the use of our website.</p>

<p>From our website, you can visit other websites by following hyperlinks to such external sites. While we strive to provide only quality links to useful and ethical websites, we have no control over the content and nature of these sites. These links to other websites do not imply a recommendation for all the content found on these sites. Site owners and content may change without notice and may occur before we have the opportunity to remove a link which may have gone 'bad'.</p>

<p>Please be also aware that when you leave our website, other sites may have different privacy policies and terms which are beyond our control. Please be sure to check the Privacy Policies of these sites as well as their "Terms of Service" before engaging in any business or uploading any information.</p>

<h2>Consent</h2>

<p>By using our website, you hereby consent to our disclaimer and agree to its terms.</p>

<h2>Update</h2>

<p>Should we update, amend or make any changes to this document, those changes will be prominently posted here.</p>
      <span class="close-btn" data-popup="#toolsPopup">&times;</span>
    </div>
  </div>

  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.4/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
  <script>
    // Get the HTML input and XML output elements
    const htmlInput = document.getElementById('htmlInput');
    const xmlOutput = document.getElementById('xmlOutput');

    // Get the convert button
    const convertBtn = document.getElementById('convertBtn');

    // Get the download button
    const downloadBtn = document.getElementById('downloadBtn');

    // Add click event listener to the convert button
    convertBtn.addEventListener('click', () => {
      const htmlCode = htmlInput.value;
      const xmlCode = convertToXML(htmlCode);
      xmlOutput.value = xmlCode;
      downloadBtn.href = `data:text/xml;charset=utf-8,${encodeURIComponent(xmlCode)}`;
    });

    // Function to convert HTML to XML
    function convertToXML(htmlCode) {
      // Your conversion logic goes here
      // Replace this placeholder logic with your own implementation

      // Replace < and > symbols with their XML entities
      const encodedCode = htmlCode.replace(/</g, '&lt;').replace(/>/g, '&gt;');

      // Generate XML output
      const xmlCode = `&lt;xml&gt;\n${encodedCode}\n&lt;/xml&gt;`;
      return xmlCode;
    }

    // Popup functionality
    const popupLinks = document.querySelectorAll('.popup-link');
    const closeBtns = document.querySelectorAll('.close-btn');

    popupLinks.forEach(link => {
      link.addEventListener('click', () => {
        const popupSelector = link.dataset.popup;
        const popup = document.querySelector(popupSelector);
        popup.style.display = 'block';
      });
    });

    closeBtns.forEach(btn => {
      btn.addEventListener('click', () => {
        const popupSelector = btn.dataset.popup;
        const popup = document.querySelector(popupSelector);
        popup.style.display = 'none';
      });
    });
    // Get the clear and copy buttons
const clearBtn = document.getElementById('clearBtn');
const copyBtn = document.getElementById('copyBtn');

// Add click event listener to the clear button
clearBtn.addEventListener('click', () => {
  xmlOutput.value = '';
});

// Add click event listener to the copy button
copyBtn.addEventListener('click', () => {
  xmlOutput.select();
  document.execCommand('copy');
});

// Add an event listener to clear the XML code when the HTML code is changed
htmlInput.addEventListener('input', () => {
  xmlOutput.value = '';
});

  </script>
</body>
</html>
