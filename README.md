# @igalaxy/presence-kit

A kit of React components for displaying user presence on various platforms

To get started:

```
npm install @igalaxy/presence-kit
OR
yarn add @igalaxy/presence-kit
```

`@igalaxy/presence-kit` currently only has one component, `Discord`.
To use:

```ts
import { Discord } from '@igalaxy/presence-kit';

export default function MyComponent() {
	return (
		<>
			<Discord id={'182292736790102017'} />
		</>
	);
}
```

_The Discord component uses [Lanyard](https://github.com/Phineas/Lanyard) to function. Ensure you are in the Lanyard Discord server or your presence will not be able to be tracked._
