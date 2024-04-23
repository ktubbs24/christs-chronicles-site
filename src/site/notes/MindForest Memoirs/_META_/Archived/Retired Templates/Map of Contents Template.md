---
{"dg-publish":true,"permalink":"/mind-forest-memoirs/meta/archived/retired-templates/map-of-contents-template/"}
---

🔺 [[🧭   Compass Rose\|🧭   Compass Rose]]
#MapofContent-note

# Map of Contents Template
---
> [!tip]- 🌱Memoir Info
>- **phase**:: #evergreen-🌲
>- **planted**:: (format2 = "YYYY-MM-DD", offset2, reference2, reference_format) => {
      if (reference2 && !window.moment(reference2, reference_format).isValid()) {
        throw new TemplaterError("Invalid reference date format, try specifying one with the argument 'reference_format'");
      }
      let duration;
      if (typeof offset2 === "string") {
        duration = window.moment.duration(offset2);
      } else if (typeof offset2 === "number") {
        duration = window.moment.duration(offset2, "days");
      }
      return window.moment(reference2, reference_format).add(duration).format(format2);
    }
>- **Related**::  



#
- 🔻 
- 🔻 
- 🔻 
- 🔻 



#
- 🔻 
- 🔻 
- 🔻 
- 🔻 
---
**see also**:: 