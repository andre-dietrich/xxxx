<!--
author:   Your Name

email:    your@mail.org

version:  0.0.1

language: en

narrator: US English Female

comment:  Try to write a short comment about
          your course, multiline is also okay.

link:   ./style.css

script: https://kit.fontawesome.com/83b2343bd4.js

@onload

window["ARCUS"] = {
    load: function(img) {
            const imgAlt = img.dataset.alt
            img.src = imgAlt

		    // Add play class to help with the styling.
		    img.classList.add('play');
    }
}

@end

-->

# xxxx
