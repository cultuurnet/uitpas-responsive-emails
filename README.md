# uitpas-responsive-emails

UiTPAS responsive emails working copy.

**Content**
- Base template, based on Cerberus framework. *https://github.com/TedGoas/Cerberus*
- Servicemails to be configured in KSB admin UI
- Milestonemails to be configured in sys admin UI

**Workflow for the creation of a new template**
1. Change the copy in the section "HTML Visually Hidden Preheader Text". 
This section is displayed as a preview in some mailclients. You wil typically insert subject line copy in here, or a one sentence summarizing of the email's content. 
3. Change the path to the logo. 
Logo's and other visuals need to be hosted on *assets.uitpas.be*
4. Change the copy
5. Verify the spelling of velocity params
6. Verify the correct application of UTM parameters (did you change *utm_source and utm_content*)
7. Test the email visually in a browser
8. Test the email via Litmus

If you need additional layout components. These can be copied out of the file *cerberus-hybrid.html* in the folder *Base*.

! Please keep the mails in the admin interfaces in sync with the GitHub repo.