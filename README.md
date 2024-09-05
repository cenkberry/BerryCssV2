# Berry Css V2 Now Live!
This css framework enables you to construct your project more efficiently by merging the structures of Bootstrap and Tailwind.

Usage:
You can modify the colors inside the :root in the _root.scss file and then 
update the breakpoints under the variables section. 
After that, you can include the global CSS file in your project and start using it right away.

You can start using the BerryCssV2.zip file above by downloading it!

Notes:
If you want to define the breakpoints in the _root.scss file within _vars.scss file and 
automatically use them in other SCSS files in your Next.js project, 
you can use the following configuration in next.config.mjs:

sassOptions: {
  includePaths: ["./src/"],
  prependData: `@import "styles/vars/_vars.scss";`
}

Tip:
If you would like to see a more detailed overview of the general usage, 
you can check out the demo page in my repository for BerryCss v1. 
Here's the link:
https://cenkberry.github.io/BerryCSS/