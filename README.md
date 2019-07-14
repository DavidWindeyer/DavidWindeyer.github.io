# DavidWindeyer.github.io

Look and feel

Prior to building my website I examined a number of sites to reflect on elements which appealed to me as something I could use in my website design.

My choice of colours for the website was based on what I saw on historical sites such as the National Trust (https://www.nationaltrust.org.au) and the Yandina Historic House (https://yandinahistorichouse.com.au)

I felt that a logo is an important part of a website.  As there was no logo image, I choose to use the intials of Churchill House (CH).  I saw a similar idea on the NGA website (https://nga.gov.au)
I used a thinner font for the logo to make it crisper and added a border to it, which was inspired by the nav border on http://www.dunnellondepot.com which I though looked like a building, and was then appropriate for a website about a building.

Learnings and challenges

My first real challenge was my header broke when I converted my site to use responsive units, em, instead of px.  Doing some research on this led me change em to rem for most of the elements, except font sizes.

On the page which gives information about Robin Boyd I wanted a clickable link to the Robin Boyd Foundation which would resize nicely.
My solution to this was to utilize a background image in the css, with a repeat setting of space, to ensure that partial images were not visable.

The size of the hero content was also interesting for me.  This involved having 3 possible displays based upon the device screen size using a media query.
As the size of the device increased so did the number of images.
I found I could easly have 3 images as the background with left, right and centre spacing.  I did investigate adding more images, but do to a non-consistant image size placement was quite difficult.

In my design I had wanted to have a carousel on the home page, but found I could not do this with CSS only.

David Windeyer - U3091705