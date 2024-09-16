# My first SPA while learning React Router and Context API

Using vite v.4 and react router v.6. In the classes css modules are explained and shows how if there are more than one nav or ul, css makes a unique id or classname for those elements.

Added a Snippet for the css module to save time importing the css files

Now learning about optimization with the react Profiler tool. Going through the app created 19 renders throughout all the components that were clicked during the test. The Ranked tabbed listed out the slowest components which were Routes (0.3ms) (quick). All renders were quick, the most coming from the datePicker (1.8ms)

Learning Code Splitting to help with bundle size by using lazy loading within React and also, adding a loading spinner with suspense that creates a conditional rendering content. Using throttling in the network section we can test the loading spinner and once you go to the previous page the browser data is save so it wont take ages to load.
