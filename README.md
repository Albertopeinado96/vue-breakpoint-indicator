# vue-breakpoint-indicator
Breakpoint indicator component for vue using tailwindcss


## Usage

## Display on the whole application

Import the component and use it inside App.vue
```
import BreakpointIndicator from '@/components/BreakpointIndicator'

<BreakpointIndicator></BreakpointIndicator>
```
## Display only on local and stage enviroment

You can check the environment to only show the components durant local or staging development. This way it will not be shown in production:
```
import BreakpointIndicator from '@/components/BreakpointIndicator'

<BreakpointIndicator v-if="process.env.NODE_ENV !== 'production'"></BreakpointIndicator>
```
