<script lang="ts">
// http://localhost:5173/

import * as m from '$paraglide/messages'

// import { setLanguageTag } from '$paraglide/runtime'
// setLanguageTag('en')

</script>

<br />
m.hello_world() : '{m.hello_world()}' // Hello World
<br />
<br />
m.greeting(name: 'John' ): '{m.greeting({ name: 'John' })}' // Hello John
<br />
Hi my friends

<!-- 
If running command from command pallette : 

Command "inlang: Extract Message"
resulted in an error
command "inlang.extractMessage" not found

Other commands fail as well

VSCode extension status page : 
Activation Event:Startup
Activation Time:118ms


If I uninstall all other extensions, uninstall Inlang, install inlang, I get : 
Activation Event:onStartupFinished
Activation Time:72ms

And still the same error
-->