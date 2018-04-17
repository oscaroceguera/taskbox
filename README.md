### Setup React storybook

```
  # Create our application:
  $ npx  create-react-app taskbox
  $ cd taskbox

  # Add storybook:
  $npx -p @storybook/cli getstorybook

  # Run the test runner (Jest) in a terminal:
  $yarn test

  # Start the component explorer on port 9009:
  $ yarn run storybook

  # Run the frontend app proper on port 3000:
  $ yarn start

  # Snapshot testing (https://github.com/storybooks/storybook/tree/master/addons/storyshots)
  $ yarn add --dev @storybook/addon-storyshots react-test-renderer

  # Get Chromatic
  $ yarn add react-chromatic
``` 