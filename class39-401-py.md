# Assets, Metadata, and CSS in NextJs

1. images
  - height={144}
  - width={144}
  - but must import - import Image from 'next/image' -
2. Metadata
  - ex: title tag
  - we can add head - import Head from 'next/head' -
  - script tag makes it easier to import third party scripts
3. CSS
  - has built-in support for styled-jsx, styled-components or emotion.
  - Tailwind CSS is also supported.

4. Layout Component
  - will be shared across all pages.
  - <Layout> ... </Layout>

5. Global Styles
  - <Component {...pageProps} />

# React Context
React context allows us to pass down and use (consume) data in whatever component we need in our React app without using props.

### When should you use React context?
- Theme data (like dark or light mode)
- User data (the currently authenticated user)
- Location-specific data (like user language or locale)

### What problems does React context solve?
- Props drilling: when you pass props down multiple levels to a nested component, through components that don't need it.

### How do I use React context?
1. Create context using the createContext method.  
> export const UserContext = React.createContext();
2. Take your created context and wrap the context provider around your component tree.  
> <UserContext.Consumer> value in here! </UserContext.Consumer>
3. put any value you like on your context provider using the value prop.

