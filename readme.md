## Notes about HTML:

Even though the labels for the inputs aren't visible in the design, your HTML should still include label tags for every input.

You can make them invisible using the following CSS snippet:

.visually-hidden { 
	border: 0; 
	clip: rect(0 0 0 0); 
	height: 1px; 
	margin: -1px; 
	overflow: hidden; 
	padding: 0; 
	position: absolute; 
	width: 1px; 
}

This will enable the labels to be read by screen readers but not visible to sighted users. This snippet was borrowed from the HTML5 Boilerplate we saw last week.

## Google Fonts options:

The GA fonts are special ones that aren't on Google Fonts but the following are close matches

Roboto Condensed or Impact for headings
Georgia for body copy

## Colours:

grey: #f6f6f6
dark grey: #dadada
red: #ff003d
dark red: #df0000