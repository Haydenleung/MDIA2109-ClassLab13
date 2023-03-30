# Environmental Variable

1. Create a file at the root of the project

```
.env
```

2. Inside the .env file add the text:

- you must use `NEXT_PUBLIC` or else this will not work

```
NEXT_PUBLIC_TITLE = "Digital Design and Development"
```

3. On the page, in between the export and report write the variable:

```
var title = process.env.NEXT_PUBLIC_TITLE;
```

4. Then in between the main tag write:

```
{title}
```

5. Make sure the `.gitignore` file has the `.env` inside

- you want to prevent the secrete title to be shown

## BCIT Data from Digital Design and Development Diploma

[Digital Design and Development Diploma Courses] (https://www.bcit.ca/programs/digital-design-and-development-diploma-full-time-6515dipma/#courses)

# Description

- This is a demonstration website using NextJS and env to show the data from the BCIT D3 Program website
- We use .env file to keep the variale in secret
- We use useState to create a Accordion

# Tools/Programming Language Used

- NextJS

# Command lines

- npx create-next-app
- npm run dev
