# CSS Specificity Bug

This repository demonstrates a common issue in CSS: unexpected style overriding due to specificity.  The `div.container` selector has higher specificity than `.container`, leading to the `lightgreen` background overriding the intended `lightcoral` background.  The solution shows how to correct this by adjusting either the selector or the order of the styles.