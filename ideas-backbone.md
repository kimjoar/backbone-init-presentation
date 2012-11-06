Gjør så mye som mulig på serveren
Enkle utvidelser av sync
Spinnere
Minnelekasjer
- bindTo over bind
Router
Pass på ansvar:
- Nettverk => Modell
- DOM => View
- URL-er => Router
Require.js - positivt og negativt
Testing
- sinon
- jasmine, pros/cons
- Node.js tilgjengelig?
- grove tester / ca integrajonstester
- mocke ajax
- views, $(<mock html>)
Layout/sections
- Hvem har ansvaret?
Tenk på komponenter
Underscore.js er kraftig
Pass på å ikke dra inn for mange avhengigheter
- Backbone er lite og enkelt å forstå
- Trenger sjelden "all magien", de tar mange valg. Vanskelig å forstå valgene uten å kjenne Backbone.


Base{View, Model, Collection}
RenderTemplate
- med og uten Require.js
- kalles med flere argumenter
Views og subviews
Hva bør skje i initialize
Ikke over-engineer i begynnelsen. Lær gradvis.
Eventer, lokale og globale
Alltid send inn `el`
Vise hvordan parse kan brukes, jf Backbone meetup
Hvordan vise views
Ikke vær redd for vanlige JavaScript-objekter
