# ShadCN Course

It solves css problems. It is a component library made on radix and it follows tailwind css.

NextJs is a full stack framework.

npx create-next-app@latest . ->> dot says install next app within that folder instead of creating a new folder

linting shows suggestive errors and its a good practice

framework has rules and this is the same kind of rules which is src/directory 

we should use modern app router, otherwise we will be facing backward compatibility issues as previously routing was been done in pity different way in nextjs

import alias with the help of @ we can do things simply and nicely. Select no as we dont want to use anything than else

say no to turbopack its for the future purpose

typescript insort give typesafety that is too define types

to run project just npm run dev

in pages.tsx remove everything except main

inside app with whatever me make the folder name, the routing is been defined by that name, so we do not need to invoke the router

note never name folder by "api" because it is defined for backend

note a concept is there that is whenever we use flex justify-center items-center it only ceters horizontally not vertically tey appliying the border-2 you will get to know that page thus needs a height which we are gooing to define in global css

shadcn is not a component library it is collection of resuable code,normally when we install component libraries their code can't be manipulated as they are present in node modules. Also we only take the code we want thus it make our app light and not bloated as other library does.

go to installation and select nextjs

copy npm command and paste to terminal it basically adds some files to our project // it adds some coniguration files to nextjs project

npx shadcn@latest init -d

yes

select newyork style, slate,src/app/globals.css, yes fr css variables, no to custom tailwind prefix

just tell file paths correct

use ctrl space to add imports faster

Shadcn default button automaticaly changes color as we gone to the layout.tsx and gave dark mde to the html element

we gave variant outline to see button differently

try variant destructive

we can define our own variants also . . . in button.tsx

Now we will see the power of shadcn by implementing a accodian

see the usage from docs and flwalessly implement it

lets try alert dialog

we can have themes also and just paste in global css.

git init // intialize the project
git add -a // add all the files to be pushed to git
git commit -m // commit with message
git add origin <url> // origin setting where to push the code
git push origin master // pushes to the master branch










