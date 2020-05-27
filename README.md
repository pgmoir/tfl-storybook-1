cd Documents/code
npx create-react-app tfl-storybook-1 --template typescript
cd tfl-storybook-1
code . -r
yarn start

OK

npx -p @storybook/cli sb init
yarn storybook

OK

>> create new repo on github tfl-storybook-1

git remote add origin https://github.com/pgmoir/tfl-storybook-1.git
git push -u origin master

>> changed *.stories.js to *.stories.tsx

>> changed main.js `stories: ['../src/**/*.stories.tsx'],`

>> changed package.json script `"build-storybook": "build-storybook -c .storybook -o build"`



