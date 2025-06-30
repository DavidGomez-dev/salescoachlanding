---
layout: single
title: "SAILES Coach HubSpot Guide"
categories: blog
tags:
  - setup guide
classes: wide no_padding_top
date: 2023-01-01 16:54:38 +0100
excerpt: Guide for installing and using SAILES Coach in HubSpot
sidebar_resume: true
header:
  overlay_image: /assets/images/zermatt.jpg
  teaser: /assets/images/zermatt.jpg
  caption:
  video:
    side: true
    id: "86ba7d2367064a80aa9f233190c3f89f?sid=3f8dc7d0-397e-4b72-909b-be3331e82590&hideEmbedTopBar=true&muted=true&autoplay=false&hide_speed=true&t=68"
    provider: "loom"
---

<div id="accordionExample" class="accordion">
<div class="accordion-item">

<h3 class="accordion-header">
<button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseInstalling" aria-expanded="true" aria-controls="collapseInstalling"><span id="start" class="pt-6-m">Getting Started</span>
</button></h3>

<div class="accordion-collapse collapse" id="collapseInstalling" data-bs-parent="#accordionExample">
<div class="accordion-body">
<h4 class="pt-6-m mb-3 text-primary" id="connect-your-hubspot-account">1. Connect Your HubSpot Account</h4>

<p>Click the <strong>Install app</strong> button below to link your HubSpot account.</p>

<p class="text-center"><a href="{{ site.pwalink }}" target="_blank" class="w-50"><img src="../../assets/images/installBtn.png" alt="Install"></a></p>

<p>You may need to grant permission to the user to install external apps. <a href="#cannot-install-app">See below</a>.</p>

<hr>

<h4 class="pt-6-m mb-3 text-primary" id="login-to-your-hubspot-account">2. Login to Your HubSpot Account</h4>

<p>Simply use your standard HubSpot login credentials.</p>

<p class="text-center"><img src="../../assets/images/guide1.png" alt="Login" class="my-3 border border-3 border-primary rounded rounded-3"></p>

<hr>

<h4 class="pt-6-m mb-3 text-primary" id="select-your-hubspot-account">3. Select Your HubSpot Account</h4>

<p>If you have multiple accounts, select the one you wish to use. Single accounts will be chosen automatically.</p>

<p class="text-center"><img src="../../assets/images/guide2.png" alt="Account" class="my-3 border border-3 border-primary rounded rounded-3"></p>

<hr>

<h4 class="pt-6-m mb-3 text-primary" id="confirm-permissions">4. Confirm Permissions</h4>

<p>Approve the necessary permissions for SAILES Coach to interface with your HubSpot CRM and click on “Connect app”. Congratulations, you have installed SAILES Coach. </p>
<p>The first user of the account is the Admin by default, but there can be more users on the same account.</p>

<p class="text-center"><img src="../../assets/images/guide21.png" alt="Permissions" class="my-3 border border-3 border-primary rounded rounded-3"></p>

<h4 class="pt-6-m mb-3 text-primary" id="adding-cards">5. Adding the Cards to the Deals, Contacts or Company records</h4>

<p>SAILES Coach is easily accessible within your HubSpot records, but you may need to configure the app card to display on your Deal, Contact, or Company record pages. You may need Super Admins must complete this setup. Follow the steps below to add the SAILES Coach card to your record views.</p>

1. In the account where you installed the app, got the Deal, Company and or Contact record and click the Customize icon in the main navigation bar.

<p class="text-center"><img src="../../assets/images/guide5n1.png" alt="Permissions" class="my-3 border border-3 border-primary rounded rounded-3"></p>

2. Click the Record customization tab. Click Default view to customize the default contact record view.

<p class="text-center"><img src="../../assets/images/guide5n2.webp" alt="Permissions" class="my-3 border border-3 border-primary rounded rounded-3"></p>

3. Click the + tab to create a new Card on Overview or a new Card on the Sidebar.

<p class="text-center"><img src="../../assets/images/guide5n3.png" alt="Permissions" class="my-3 border border-3 border-primary rounded rounded-3"></p>

In the right panel, under Card library > All card types, click Apps.

<p class="text-center"><img src="../../assets/images/guide5n4.png" alt="Permissions" class="my-3 border border-3 border-primary rounded rounded-3"></p>

Click on "Add Card" on the SAILES Cards, which should then appear on the Cards list.

<p class="text-center"><img src="../../assets/images/guide5n5.png" alt="Permissions" class="my-3 border border-3 border-primary rounded rounded-3"></p>

Click the **X** at the top of the right panel to close it. Then, in the upper-right corner, click **Save and exit**. The SAILES Coach card should now be visible on the selected record.

Repeat these steps for each record type—Deals, Contacts, and Companies—as needed. Super Admins or users with appropriate permissions may need to perform this setup for all relevant record types.

<p class="text-center"><img src="../../assets/images/guide5n6.png" alt="Permissions" class="my-3 border border-3 border-primary rounded rounded-3"></p>

</div>
</div>
</div>

<div class="accordion-item">

<h3 class="accordion-header">
<button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseUsing" aria-expanded="true" aria-controls="collapseUsing"><span id="using" class="pt-6-m">Using the APP</span>
</button></h3>

<div class="accordion-collapse collapse show" id="collapseUsing" data-bs-parent="#accordionExample">
<div class="accordion-body">

<h4 class="pt-6-m mb-3 text-primary" id="access-from-sidebar">6. Access SAILES Coach from the HubSpot Middle or Side Cards </h4>

<p>SAILES Coach is available in Deals, Contacts, and Companies. You can access it either in the main (middle) section as a detailed summary or in the sidebar as a concise executive overview. Each view provides tailored information relevant to the specific record type, helping you quickly understand key insights and next steps.</p>
<p>
  The analysis displayed is the most recent available, but it may become outdated over time. Users can generate a new analysis at any moment by clicking the <strong>Redo Analysis</strong> button.
</p>

<p>
  In the middle section, the complete assessment can be copied to the clipboard by clicking the <strong>Copy</strong> button.
</p>

<h5 class="pt-6-m mb-3 text-primary" id="deals">Deals</h5>

<p>
  The information shown for each Deal includes:
</p>
<ul>
  <li>A summary line providing a quick overview.</li>
  <li>A progress bar indicating the probability of closure (0–100), calculated holistically by the AI model.</li>
  <li>A summary of the Deal, highlighting important details such as deal stage, value, and expected close date.</li>
  <li>An action plan with recommended next steps, including suggested activities or follow-ups to advance the deal.</li>
  <li>Related contacts and their roles or implications for the deal, helping you identify key stakeholders and decision-makers.</li>
  <li>Key points for messaging and communication, offering guidance on how to engage with the client or prospect effectively.</li>
</ul>

<p class="text-center"><img src="../../assets/images/deal-card-tab.png" alt="Access from Sidebar" class="my-3 border border-3 border-primary rounded rounded-3"></p>
<p class="text-center"><img src="../../assets/images/deal-card-side.png" alt="Access from Sidebar" class="my-3 border border-3 border-primary rounded rounded-3"></p>

<h5 class="pt-6-m mb-3 text-primary" id="contacts">Contacts</h5>

<p>
  For each Contact, SAILES Coach provides:
</p>
<ul>
  <li>A concise summary of the contact's past engagements, including an evaluation of the relationship—covering their attitude, engagement level, and any relevant context.</li>
  <li>An actionable one-line next step for the user, indicating what to discuss with the contact and which Deal(s) it relates to.</li>
  <li>A summary of the contact's involvement in each Deal, including the deal name, a one-line status summary, and a unique identifier for each deal.</li>
  <li>Key talking points or topics to address in the next interaction, tailored to recent activity and referencing the relevant deals.</li>
  <li>Clicking on Email, a draft email suggestion, including a subject and body, summarizing key points and next steps, and inviting further engagement in a friendly, professional tone.</li>
  <li>A rapport indicator (disengaged, neutral, engaged, or champion) that evaluates the strength of the relationship based on the number, recency, and quality of interactions, as well as the contact's attitude.</li>
</ul>
<p class="text-center"><img src="../../assets/images/contact-card-tab.png" alt="Access from Sidebar" class="my-3 border border-3 border-primary rounded rounded-3"></p>
<p class="text-center"><img src="../../assets/images/contact-card-side.png" alt="Access from Sidebar" class="my-3 border border-3 border-primary rounded rounded-3"></p>

<h5 class="pt-6-m mb-3 text-primary" id="companies">Companies</h5>

<p>
  For each Company, SAILES Coach provides:
</p>
<ul>
  <li>A concise summary of the company's relationship, engagement level, and sales potential.</li>
  <li>A one-line actionable next step for the user to take with this company.</li>
  <li>A summary of ongoing deals, each showing the deal name, a unique identifier, and a one-line status or next step.</li>
  <li>A summary of related contacts, each with their name, unique identifier, and a brief note on their involvement or relationship.</li>
  <li>A list of key opportunities or risks identified for this company.</li>
  <li>A prioritized action plan to strengthen the relationship and advance sales.</li>
  <li>An overall company health indicator: "at risk", "neutral", "engaged", or "strategic".</li>
</ul>
<p class="text-center"><img src="../../assets/images/company-card-tab.png" alt="Access from Sidebar" class="my-3 border border-3 border-primary rounded rounded-3"></p>
<p class="text-center"><img src="../../assets/images/company-card-side.png" alt="Access from Sidebar" class="my-3 border border-3 border-primary rounded rounded-3"></p>

<hr>

<h4 class="pt-6-m mb-3 text-primary" id="upgrade-to-premium">7. Upgrade to Premium</h4>

<p>
The free plan of SAILES Coach allows you to evaluate up to 5 Deals, 5 Contacts, and 5 Companies.  
If you find SAILES Coach valuable and want to unlock unlimited evaluations and premium features, you can upgrade directly within the app. Simply click “Upgrade Now” to access a secure Stripe-powered checkout.
</p>

<p class="text-center"><img src="../../assets/images/guide7n1.png" alt="Ugrade" class="my-3 border border-3 border-primary rounded rounded-3"></p>

<p class="text-center"><img src="../../assets/images/guide7n2.png" alt="Ugrade" class="my-3 border border-3 border-primary rounded rounded-3"></p>
<hr>

<h4 class="pt-6-m mb-3 text-primary" id="changeplan">8. Change the subscription plan</h4>

<p>If you're already enjoying the premium benefits of SAILES Coach but want to upgrade to a Team plan or switch to a yearly subscription to unlock significant savings, you can easily make the change through the Customer Portal. Take advantage of these exclusive discounts today and maximize your SAILES Coach experience!</p>

<p class="text-center"><img src="../../assets/images/trouble5.png" alt="troubleshooting" class="mt-5 w-50 border border-3 border-primary rounded rounded-3"></p>

<p class="text-center"><img src="../../assets/images/guide51.png" alt="Ugrade" class="my-3 border border-3 border-primary rounded rounded-3"></p>

<p class="text-center"><img src="../../assets/images/guide52.png" alt="Ugrade" class="my-3 border border-3 border-primary rounded rounded-3"></p>
</div>
</div>
</div>

<div class="accordion-item">

<h3 class="accordion-header">
<button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseUninstall" aria-expanded="true" aria-controls="collapseUninstall"><span id="uninstalling" class="pt-6-m">Uninstalling the APP</span>
</button></h3>

<div class="accordion-collapse collapse" id="collapseUninstall" data-bs-parent="#accordionExample">
<div class="accordion-body">

<p>If you are a paid or premium user, you  need to cancel your subcription before uninstalling, by visiting the Customer Portal. <a href="#how-can-cancell-or-manage-my-subcription">More information.</a></p>

<p>Additionally, you may want to delete all the data stored in MeddiccScore, including users and account information, before uninstalling. <a href="#manage-account">More information.</a> If you plan to reinstall the app later, the data will reappear unless the account has been deleted beforehand.</p>

<p>To uninstall, navigate to <strong>Settings &gt; Integrations &gt; Connected Apps</strong>. Click in Actions and then "Uninstall". This will uninstall SAILES Coach without impacting your HubSpot data.</p>

<p class="text-center"><img src="../../assets/images/guide6.png" alt="Uninstall" class="my-3 border border-3 border-primary rounded rounded-3"></p>

</div>
</div>
</div>

<div class="accordion-item">

<h3 class="accordion-header">
<button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTrouble" aria-expanded="true" aria-controls="collapseTrouble"><span id="troubleshooting" class="pt-6-m">Troubleshooting</span>
</button></h3>

<div class="accordion-collapse collapse show" id="collapseTrouble" data-bs-parent="#accordionExample">
<div class="accordion-body">

<h4 id="cannot-install-app" class="pt-6-m mb-3 text-primary">I cannot install the APP<a class="header-link" href="#cannot-install-app" title="Permalink"><span class="sr-only">Permalink</span><i class="fas fa-link"></i></a></h4>

<p>Please check that the user has permission to install external apps from the marketplace. Users must be either a super admin or have <a href="https://knowledge.hubspot.com/user-management/hubspot-user-permissions-guide?hubs_content=knowledge.hubspot.com/integrations/connect-apps-to-hubspot&hubs_content-cta=app-marketplace-access#settings" target="_blank">App Marketplace Access permissions</a> or <a href="https://knowledge.hubspot.com/user-management/hubspot-user-permissions-guide?hubs_content=knowledge.hubspot.com/integrations/connect-apps-to-hubspot&hubs_content-cta=super-admin#super-admin" target="_blank">Super Admin permissions</a> to connect apps to their HubSpot account.</p>

<p class="text-center"><img src="../../assets/images/trouble13.png" alt="troubleshooting" class="my-3 border border-3 border-primary rounded rounded-3"></p>

<p>For more information on user permissions, visit the <a href="https://knowledge.hubspot.com/user-management/hubspot-user-permissions-guide?#account" target="_blank">HubSpot User Permissions Guide</a>.</p>

<hr>

<h4 id="i-cannot-see-score-as-a-custom-variable--the-score-in-hubspot-is-not-updated-automatically" class="pt-6-m mb-3 text-primary">I cannot see Score as a property / The Score property in HubSpot is not updated automatically<a class="header-link" href="#i-cannot-see-score-as-a-custom-variable--the-score-in-hubspot-is-not-updated-automatically" title="Permalink"><span class="sr-only">Permalink</span></a></h4>

<p>To enable this, you may need to reauthorize the app for the new permits required. Please click here</p>

<p class="text-center"><a href="{{ site.pwalink }}" target="_blank"><img src="../../assets/images/installBtn.png" alt="Install"></a></p>

<p>You may also need before that, to have permits to add new properties (or someone else who has authorized the app with all the permits). Partner accounts with permits may be not enough. For reference, the Scope requiered is "crm.pipelines.orders.write".</p>

<p class="text-center"><img src="../../assets/images/trouble1.png" alt="troubleshooting" class="my-3 border border-3 border-primary rounded rounded-3"></p>

<p>If does not work even after re-installation, then user needs to <i>create the variable manually</i>. It can be done in <strong>Settings > Data Management > Properties > Create property</strong>:</p>

<p class="text-center"><img src="../../assets/images/trouble12.png" alt="troubleshooting" class="my-3 border border-3 border-primary rounded rounded-3"></p>

<p>It is very important to make it work that:</p>

<ul>
  <li>The internal name be exactly “score_meddicc”</li>
  <li>Object type is “Deal”</li>
  <li>Group is “Deal information”</li>
  <li>The property label “Score” (but it can be different)</li>
</ul>

<p class="text-center"><img src="../../assets/images/trouble2.png" alt="troubleshooting" class="my-3 w-50 border border-3 border-primary rounded rounded-3"></p>

<ul>
  <li>"Field type": # Number</li>
  <li>"Number format": Formatted number</li>
</ul>

<p class="text-center"><img src="../../assets/images/trouble21.png" alt="troubleshooting" class="my-3 w-50 border border-3 border-primary rounded rounded-3"></p>

<p>These are optional but recommended for validation:</p>
<ul>
  <li>"Set min value limit": 0</li>
  <li>"Set max value limit": 100</li>
  <li>"Set max number of decimal places": 0</li>
</ul>

<p class="text-center"><img src="../../assets/images/trouble22.png" alt="troubleshooting" class="my-3 w-50 border border-3 border-primary rounded rounded-3"></p>

<hr>
<h4 id="the-ai-autofill-is-not-taking-information-from-my-emails" class="pt-6-m mb-3 text-primary">The AI Autofill is not taking information from my Emails<a class="header-link" href="#the-ai-autofill-is-not-taking-information-from-my-emails" title="Permalink"><span class="sr-only">Permalink</span><i class="fas fa-link"></i></a></h4>

<p>To enable this, you may need to reauthorize the app for the new permits required (access to read emails basically). Please click here:</p>

<p class="text-center"><a href="{{ site.pwalink }}" alt="Install" class="w-10">
<img src="../../assets/images/installBtn.png" alt="Install"></a></p>

<p>In all cases, the information extracted from emails is limited to the initial portion of each email. This helps avoid processing repetitive long threads, legal disclaimers, and other non-essential content. However, if critical Deal information is buried deep within the email threads or other engagements, the AI might not capture or interpret it accurately. Also AI tends to allucinate sometimes, please check important facts.</p>

<hr>
<h4 id="stage-report" class="pt-6-m mb-3 text-primary">The Stage is not correct on the report<a class="header-link" href="#stage-report" title="Permalink"><span class="sr-only">Permalink</span><i class="fas fa-link"></i></a></h4>

<p>The Stage property in HubSpot can be modified. Ensure that the internal name for lost opportunities includes the string "lost" and for won opportunities, it includes the string "won". Note that sometimes the internal name might be a number, which is the standard when the stage is created.</p>

<p class="text-center"><img src="../../assets/images/trouble7.png" alt="troubleshooting" class="mt-5 w-50 border border-3 border-primary rounded rounded-3"></p>

<hr>

<h4 id="how-can-add-a-discount-code" class="pt-6-m mb-3 text-primary">How can add a discount code<a class="header-link" href="#how-can-add-a-discount-code" title="Permalink"><span class="sr-only">Permalink</span><i class="fas fa-link"></i></a></h4>

<p>On the checkout Stripe page, there is a button ‘Add Code’ where you can add yu discount code. The price will be automatically updated. If you face any problem or the code not longer works, please <a href="mailto:meddiccscore@gmail.com">Contact Us</a>:</p>

<p class="text-center"><img src="../../assets/images/trouble4.png" alt="troubleshooting" class="mt-5 w-50 border border-3 border-primary rounded rounded-3"></p>

<p class="text-center"><img src="../../assets/images/trouble3.png" alt="troubleshooting" class="mb-3 w-50 border border-3 border-primary rounded rounded-3"></p>

<p>If you already have a subscription and want to add a coupon code, it cannot be done automatically, please <a href="mailto:meddiccscore@gmail.com">Contact Us</a></p>

<hr>

<h4 id="how-can-cancell-or-manage-my-subcription" class="pt-6-m mb-3 text-primary">How can I cancel or manage my subscription?<a class="header-link" href="#how-can-cancell-or-manage-my-subcription" title="Permalink"><span class="sr-only">Permalink</span><i class="fas fa-link"></i></a></h4>

<p>If you want to cancel your subscription or change the invoice details, you can access the Customer Portal (or send and email to Support) by clicking on “Subscription” button inside the settings. (Only admin users)</p>
<p>Please cancell your subscription BEFORE uninstalling the APP, since the latter does not automatically cancel de subcription. (this is a HubSpot limitation)</p>

<p class="text-center"><img src="../../assets/images/trouble5.png" alt="troubleshooting" class="mt-5 w-50 border border-3 border-primary rounded rounded-3"></p>

<p class="text-center"><img src="../../assets/images/trouble6.png" alt="troubleshooting" class="mb-5 border border-3 border-primary rounded rounded-3"></p>

</div>
</div>
</div>
</div>
