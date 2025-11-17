# CSS Cascade Activity
For each of the following `<p>` elements, list all the CSS rules that apply to its color, identify the final applied value, and explain why that value is used.

* For `<p id="mission">`
    * body { color: #333 }
    * p { color: black } 
    * #mission { color: darkorange }
    * .text { color: #555 }

    The color that will be applyied will be darkorange because it is an id and has more Specifity than the text Class.

* For `<p id="team">`
    * body { color: #333 }
    * p { color: black }
    * style = "color: darkblue"
    * .text { color: #555 }

    The color that will be applyied will be darkblue because it is an html embeded style so its Specifity is bigger.

* For `<p id="experience">`
    * body { color: #333 }
    * p { color: black }
    * .text { color: #555 }
    * #experience { color: darkgray }
    * #about p:last-child { color: green }

    The color that will be applyied will be green because it is an id and specifies a p last child so it has more Specifity.

* For `<p id="services-intro">`
    * body { color: #333 }
    * p { color: black }
    * .text { color: #555 }
    * .intro { color: blue }

    The color that will be applyied will be blue because it is the last element with a color specification so it has more Specifity than the text class.

* For `<p id="offer">`
    * body { color: #333 }
    * p { color: black }
    * #offer { color: darkgreen !important }
    * style = "color: darkblue"

    The color that will be applyied will be darkgreen because it is an id with an !important specification so it has more Specifity than the embeded html style.