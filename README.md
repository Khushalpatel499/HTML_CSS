# HTML_CSS

1. html stands for hyperText markup language,it is a hirechical strucutre( hypertext means we can redirect user in other docuements or in other section)(markup means use of elements by tag to indicate where one particular element start and one end )(html element meainig opening tag , content,closing tag).
2. html is a markup language that web developers use to structure and describe the content of a webpage(not a programming language)
3. html consist of element that describe different type of content: paragraphs,links,headings,images,video etc.
   4.web browsers understand html and render html code as website.
4. world wide web is collection of interlink documents.
5. it use the client struture architecure.
6. html (for strucutre) + css(for design) + javascript(for interactive)
7. client request the server for resources and server response the request by give resources is called client server architecutre
8. if the content is same for all users(not user specific) than the website is called static website.
9. if the content is relavent to user or user sepecific than the website is called dynamic website.
   10.client side(front end side ) is basially the user side which is responsible for better presentation, not consern about data.
10. server side (backend side) to store the data and provide to frontend side.
11. all the device connected to internet have a unique identifier is called ip address which is responsible for give the inforamtion but we genarally not type ip address all the time we used the domain name. TO get the ip address we need DNS
    (domain name system)
12. so the procees is that client provide url then it goes to isp(internet service provider) with the domain name then isp search the given dns then provide desired ip address and then contact to server and establish a connection between client and server.
13. html tag have two fixed children called head and body(whatever part visible on page come under body section).
14. head part is about metadata which is generally some information about the page 15.<!DOCTYPE html> this indicate browser to that we are using html 5

#CSS
1.cascading style sheets
2.it describe the visual style and presentation of the content written in html
3.CSS consist of countless properties that developers use to format the content: properties about font,text,spacing,layout etc.
ex: h1{
color:blue;
}
4.in above code h1 is selector and color is property and blue is value and property with value together is declaration/style ,all this declartion or style make together a declaration block which put in{}. all together are called css rule

5.there are three places where we can write css is inline,internal and external css
6.inline css write inside the html element
7.in internal css we declare a style element in head.

IMP:
WEB DESIGN
1.Divide in 9 different areas of design : ingredients
a.Typography : formatting and designing of text.
b.Colors.
c.Images/Illustrations
d.Icons
e.Shadows
f.Border-radius
g.Whitespace
i.Visual Hierarchy
j.User Experience
k.Components/Layout
2.Desgin decisions for each ingredient are based on website personality.

A.Typography
ex :serif and sans-serif
1.tool box: google fonts ,font squirrels 2. use a font size between 16px and 32 px for normal text. 3. for any text,dont use a font weight under 400(regular)
4.use less than 75 characters per line
5.for normal sized text,use a line height between 1.5
and 2 .for big text,go below 1.5
tip: the smaller or longer the text,the larger the line height. 6.Usually don't justify text.
imp.tool for font size: type-scale.com

B.Color
tools: open color,tailwindcss,flat ui colors2,tint and shade generator, coolors, palleton.com

1.we need at least two type of colors in your color palette:a main color and a grey color. 2. with more experience ,you can add more colors: accent colors(use tool) 3. for diversity,create lighter and darker "versions"(tints and shades)

2.on dark colored backgrounds,try to use a tint of the background(lighter version") for text. 3.
3.text should usually not be completely black.Lighten if up it look heavy and uninviting.
4.Don't make text too light use tool(coolors) to check contrast between text and background colors.
tip: contrast ratio needs to be at least 4.5:1 for noramal text and 3:1 for large text(+18px)

C.Images:
tools: unsplash,pexels,drawkit,undraw
1.to account for high-res screens,make image dimensions 2x as big as their displayed size.
2.compress images for a lower file size and better performance.
toolbox: squoosh

D.icons:
tools: phosphor icons,ionicons,icons8,heroicons
1.use svg icons or icon font(they are vector based and scale indefinitely).dont use bitmap image formats(.jpg and .png)

E.Shadows:
1.shadows creates depth(3D) , the more shadow ,the further away from the interface the element is
2.shadow can be used on boxes and text.
3.use shadow in small does,dont add shadow to every element
4.go light on shadow, don't make them too dark.
syntax: box-shadow: horizontaloffsetoftheshadow verticaloffsetoftheshadow bluroftheshadow scaletheshadowup(optional) coloroftheshadow

F.Border radius:
1.use border-radius on buttons,images,around icons,standout sections and other elements.

G.WHite space
1.right amount of whitespace make design look clean,modern,and polished.

H.Visual hierarchy:
1.is about establishing which element of a design are the most important ones.
2.we use a combination of position,size,colors,spacing,borders,and shadow to establish a meaningful visual hierarchy between elements/componenets.

I.USER EXperience(UX)

1.User Interface(UI) is the visual presentation of a product.It how the graphical interface looks and feel like.
2.User Experience(UX) is the overall experience the user has while interacting with the product.

IMP: steal like artist:
websites: land-book,onepagelove,awwwards.com
,screenlane.com,appsingal,docspo.com
