# Links Markup
Links are the defining feature of the web because they allow you to move from one web page to another - enabling the very idea of browsing
Links are created using the 'a' element. 
The text between the opening 'a' tag and the closing 'a' tag is known as link text. Where possible, link text should explain where visitors will be taken if they click on it (rather than just saying "click here")
'a' element has an attribute 'href'. The value of 'href' attribute is the page or section that you want people to go when they click on the link.
- When you link to a different website, the value of the 'href' attribute will be the full web address of the site, which is the <b>absolute</b> URL.
- When linking to other pages within the same site, you do not need to specify the domain name in the URL. You can use a shorthand link known as a <b>relative</b> URL.
- To create a link that starts up the user's email program and addresses and email to a specified email address, you use the 'a' element. However, this time the value of the 'href' attribute starts with 'mailto:' and followed by the email address you want the email to be sent to.
- If you want a link to open in a new window, you can use the 'target' attribute on the opening 'a' tag. The value of this attribut should be "_blank".
- To link to a specific part of the same page, you need to identify the points in the page that the link will go to. This is done using the 'id' attribute. The value of the 'id' attribute should start with a letter or an underscore. To link to an element that uses an 'id' attribute you use the 'a' element, but the value of the href attribute starts with the # symbol, followed by the value of the 'id' attribute of the element you want to link to.
- You can also link to a specific part of another page provided the other page has 'id' attributes that identify specific parts of the page.
