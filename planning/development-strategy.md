# Development strategy

## SET UP

- [ ] create `index.html`
- [ ] link `style.css` file to `index.html`
- [ ] put all the images in `public` file

## Title

> As a user I want to see a clear title for the website. There is a good title
> that user can see in top of the page.

- HTML Put "Hack Your Future" text in `<title>` tag of the `<head>` part.

## Website logo

> As a user I want to see a logo for the website. There is a logo the reflects
> the website title.

- HTML Use `<img>` tag to insert HYF logo image.

- CSS Style the website logo to the top left of the page using flexbox or grid,
  to be aligned with the navbar.

## Navbar

> As a user I want to have a navigation bar to go to different pages of the
> website. There is navigation bar with links to all pages in website.

- HTML Use `<ul>` and `<li>` tag to list out different `<a>` link for the navbar
  .

- CSS Style the link text to color `rgb(127, 127, 127)`. When hover through, the
  link text should turn black and show thick purple bottom line.

## Main info section

> As a user I want to have main section explaining what the program is about.
> There is a section with extra information button that explains what the
> program is.

- HTML Use `<section>` tag to divide different part of the information . If
  needed, add a "discover more" button with `<button>` tag below the text part
  to link to more complete information.

- CSS "OUR PROGRAM" section text should be left-aligned, "OUR IMPACT" section
  text should be centre-aligned. The background color of the button should turn
  gray when hover through.

## Successful examples/results

> As a user I want to see the impact of this program and its results to see if
> its successful. There is a section with some examples of program effects on
> society.

- HTML Use `<div>` to separate different success stories. Add `<img>` ,`<h4>`
  and `<p>` to demonstrate each ex-trainee's photo, current job and story.

- CSS The image should be black and white. The name/company is color
  `rgb(28, 34, 148)` . The job title is color `#4A50BB` . All text are
  centre-aligned.

## Footer

> As a user I want to see footer with social media links of the program and
> contact information. There is a footer at end of page with contact information
> on the program.

- HTML Use `<form>` to create a contact form. Use `<iframe>` to embed a map with
  HYF address if possible. Add `<svg>` images for the social media links at the
  bottom of the footer.

- CSS The background of the contact form is `rgb(74, 80, 187)`, text color is
  white. The footer text is color `rgb(28, 34, 148)` and `rgb(45, 48, 55)`,
  centre-aligned.

<<<<<<< HEAD
<<<<<<< HEAD
## The program

> - As a potential student I want to see a page to introduce the program and to
>   have a button to apply for this program. There is a `the program` page with
>   the introduction of the program and a button link to the admission form.

- HTML Add a `the program` page link in the navbar of index.html.

> - As a potential student I want to know what are the admission requirement for
>   this program. There is a list of the admission requirements in `the program`
>   page.

- HTML Add a `<section>` with a list by `<ul>`, `<li>` for admission
  requirements.

- CSS Set background color as`rgb(248, 249, 252)`.

## Volunteer

> - As a potential volunteer, I want to see a page with the information to join
>   as a volunteer. There is a `volunteer` page with the introduction of the way
>   to join as volunteer and a link to the application form.

- HTML Add a `volunteer` page link in the navbar of index.html. Add 2 links by
  `<a>` separately for joining as mentor and coach.

- CSS Style the buttons with the properties below:

1.  background-color: rgb(74, 80, 187);
2.  color: white;
3.  padding: 10px 20px;
4.  text-transform: uppercase;
5.  font-family: "Work Sans", sans-serif;

> - As a potential volunteer, I want to know what's the reason I should consider
>   joining HYF as a volunteer. There is a list to describe the advantages to
>   become a volunteer at HYF.

- HTML Add a section with a `<h3>` and 4 `<div>` to display the advantages.

- CSS Use `display:flex` to display the advantages `<div>` as 2 x 2 blocks.

## Digitalents

> - As a student or someone who's interested in coding, I want to know what's
>   the digitalents program. There is a introduction text to introduce
>   digitalents program on `digitalents` page.

- HTML Add a `digitalents` page link in the navbar of index.html. And add `<h5>`
  as title and `<p>` as intro text.

- CSS Use `text-align: center;` to style the text.

> - As a student or someone who's interested in coding, I want to know what are
>   the different program of digitalents. There are several blocks to introduce
>   different program of digitalents on`digitalents` page.

- HTML Add a section with 2 `<div>` include a `<h2>` and `<p>` to display the
  different program of digitalents.

- CSS Use `display:flex` to display the different program of digitalents.

> - As a student or someone who's interested in coding, I want to know how can I
>   apply for digitalents program. There is a button link to application form of
>   digitalents program at the bottom of `digitalents` page.

- HTML Add a section with a `<h3>` and 4 `<div>` to display the advantages.

- CSS Use `display:flex` to display the advantages `<div>` as 2 x 2 blocks.

## About

> - As a user, I want to know the core values of HYF. There is a banner with all
>   the HYF core values listed `about` page.

- HTML Add a section on the top of `about` page, add 5 `<div>` with `<img>` and
  `<h3>` text .

- CSS Use `display:flex` to display the core values as 1 x 5 blocks.

> - As a user, I want to know the team members of HYF. There is a introduction
>   of HYF core members on `about` page.\_

- HTML Add a section with 3 main `<div>` include `<img>`, `<h3>`, `<p>` and 2
  `<a>` include `<img>`.

- CSS

`<div>`

1.  box-shadow: rgba(0, 0, 0, 0.1) 5px 4px 8px 5px;
2.  padding: 20px 40px;
3.  border-radius: 7px;

`<img>`

1.  width: 180px;
2.  height: 180px;
3.  object-fit: cover;
4.  border-radius: 100%;
5.  filter: grayscale(1);

## FAQ

> - As a potential student/volunteer/partner, I want to know find the answers of
>   some common questions. There is a blocks of answers of some common questions
>   about student/volunteer/partner on `FAQ` page.

- HTML Add a `FAQ` page link in the navbar of index.html.

> - As a potential student/volunteer/partner, I want to know find the answers of
>   some common questions. There is a blocks of answers of some common questions
>   about student/volunteer/partner on `FAQ` page.

- HTML Add a search `<input>` on the top left of the page.

- CSS Use the following properties to style the `<input>`:

1.  flex-grow: 1;
2.  border: none;
3.  padding: 12px 10px;
4.  color: rgb(74, 80, 187);.

## Support us

> - As a potential partner, I want to know why should I support HYF and what are
>   the advantages. There is a introduction text to invite people or companies
>   to be the partners of HYF on the top of `support us` page.

- HTML Add a `support us` page link in the navbar of index.html, with `<p>` for
  intro text and `<a>` for contact link.

> - As a user, I want to support HYF by donating money. There is a donation form
>   on `support us` page.

- HTML Add a `<section>`with a `<form>` donation form. Use `<ul>`,`<li>` to list
  out the amount that visitors want to donate. Add `<input>` to allow visitors
  modify the amount oof donation or leave a message.

- CSS When hover, the button of amount become:

1.  background-color: rgb(28, 34, 148);
2.  color: white;

​

## The program

> - As a potential student I want to see a page to introduce the program and to
>   have a button to apply for this program. There is a `the program` page with
>   the introduction of the program and a button link to the admission form.

- HTML Add a `the program` page link in the navbar of index.html.

> - As a potential student I want to know what are the admission requirement for
>   this program. There is a list of the admission requirements in `the program`
>   page.

- HTML Add a `<section>` with a list by `<ul>`, `<li>` for admission
  requirements.

- CSS Set background color as`rgb(248, 249, 252)`.

## Volunteer

> - As a potential volunteer, I want to see a page with the information to join
>   as a volunteer. There is a `volunteer` page with the introduction of the way
>   to join as volunteer and a link to the application form.

- HTML Add a `volunteer` page link in the navbar of index.html. Add 2 links by
  `<a>` separately for joining as mentor and coach.

- CSS Style the buttons with the properties below:

  1. background-color: rgb(74, 80, 187);
  2. color: white;
  3. padding: 10px 20px;
  4. text-transform: uppercase;
  5. font-family: "Work Sans", sans-serif;

> - As a potential volunteer, I want to know what's the reason I should consider
>   joining HYF as a volunteer. There is a list to describe the advantages to
>   become a volunteer at HYF.

- HTML Add a section with a `<h3>` and 4 `<div>` to display the advantages.

- CSS Use `display:flex` to display the advantages `<div>` as 2 x 2 blocks.

## Digitalents

> - As a student or someone who's interested in coding, I want to know what's
>   the digitalents program. There is a introduction text to introduce
>   digitalents program on `digitalents` page.

- HTML Add a `digitalents` page link in the navbar of index.html. And add `<h5>`
  as title and `<p>` as intro text.

- CSS Use `text-align: center;` to style the text.

> - As a student or someone who's interested in coding, I want to know what are
>   the different program of digitalents. There are several blocks to introduce
>   different program of digitalents on`digitalents` page.

- HTML Add a section with 2 `<div>` include a `<h2>` and `<p>` to display the
  different program of digitalents.

- CSS Use `display:flex` to display the different program of digitalents.

> - As a student or someone who's interested in coding, I want to know how can I
>   apply for digitalents program. There is a button link to application form of
>   digitalents program at the bottom of `digitalents` page.

- HTML Add a section with a `<h3>` and 4 `<div>` to display the advantages.

- CSS Use `display:flex` to display the advantages `<div>` as 2 x 2 blocks.

## About

> - As a user, I want to know the core values of HYF. There is a banner with all
>   the HYF core values listed `about` page.

- HTML Add a section on the top of `about` page, add 5 `<div>` with `<img>` and
  `<h3>` text .

- CSS Use `display:flex` to display the core values as 1 x 5 blocks.

> - As a user, I want to know the team members of HYF. There is a introduction
>   of HYF core members on `about` page.\_

- HTML Add a section with 3 main `<div>` include `<img>`, `<h3>`, `<p>` and 2
  `<a>` include `<img>`.

- CSS

`<div>`

1. box-shadow: rgba(0, 0, 0, 0.1) 5px 4px 8px 5px;
2. padding: 20px 40px;
3. border-radius: 7px;

`<img>`

1. width: 180px;
2. height: 180px;
3. object-fit: cover;
4. border-radius: 100%;
5. filter: grayscale(1);

## FAQ

> - As a potential student/volunteer/partner, I want to know find the answers of
>   some common questions. There is a blocks of answers of some common questions
>   about student/volunteer/partner on `FAQ` page.

- HTML Add a `FAQ` page link in the navbar of index.html.

> - As a potential student/volunteer/partner, I want to know find the answers of
>   some common questions. There is a blocks of answers of some common questions
>   about student/volunteer/partner on `FAQ` page.

- HTML Add a search `<input>` on the top left of the page.

- CSS Use the following properties to style the `<input>`:

1. flex-grow: 1;
2. border: none;
3. padding: 12px 10px;
4. color: rgb(74, 80, 187);.

## Support us

> - As a potential partner, I want to know why should I support HYF and what are
>   the advantages. There is a introduction text to invite people or companies
>   to be the partners of HYF on the top of `support us` page.

- HTML Add a `support us` page link in the navbar of index.html, with `<p>` for
  intro text and `<a>` for contact link.

> - As a user, I want to support HYF by donating money. There is a donation form
>   on `support us` page.

- HTML Add a `<section>`with a `<form>` donation form. Use `<ul>`,`<li>` to list
  out the amount that visitors want to donate. Add `<input>` to allow visitors
  modify the amount oof donation or leave a message.

- CSS When hover, the button of amount become:

1. background-color: rgb(28, 34, 148);
2. color: white;
=======
=======
## The program
>>>>>>> ae916f3 (update)

> - As a potential student I want to see a page to introduce the program and to
>   have a button to apply for this program. There is a `the program` page with
>   the introduction of the program and a button link to the admission form.

- HTML Add a `the program` page link in the navbar of index.html.

> - As a potential student I want to know what are the admission requirement for
>   this program. There is a list of the admission requirements in `the program`
>   page.

- HTML Add a `<section>` with a list by `<ul>`, `<li>` for admission
  requirements.

- CSS Set background color as`rgb(248, 249, 252)`.

## Volunteer

> - As a potential volunteer, I want to see a page with the information to join
>   as a volunteer. There is a `volunteer` page with the introduction of the way
>   to join as volunteer and a link to the application form.

- HTML Add a `volunteer` page link in the navbar of index.html. Add 2 links by
  `<a>` separately for joining as mentor and coach.

- CSS Style the buttons with the properties below:

  1. background-color: rgb(74, 80, 187);
  2. color: white;
  3. padding: 10px 20px;
  4. text-transform: uppercase;
  5. font-family: "Work Sans", sans-serif;

> - As a potential volunteer, I want to know what's the reason I should consider
>   joining HYF as a volunteer. There is a list to describe the advantages to
>   become a volunteer at HYF.

- HTML Add a section with a `<h3>` and 4 `<div>` to display the advantages.

- CSS Use `display:flex` to display the advantages `<div>` as 2 x 2 blocks.

## Digitalents

> - As a student or someone who's interested in coding, I want to know what's
>   the digitalents program. There is a introduction text to introduce
>   digitalents program on `digitalents` page.

- HTML Add a `digitalents` page link in the navbar of index.html. And add `<h5>`
  as title and `<p>` as intro text.

- CSS Use `text-align: center;` to style the text.

> - As a student or someone who's interested in coding, I want to know what are
>   the different program of digitalents. There are several blocks to introduce
>   different program of digitalents on`digitalents` page.

- HTML Add a section with 2 `<div>` include a `<h2>` and `<p>` to display the
  different program of digitalents.

- CSS Use `display:flex` to display the different program of digitalents.

> - As a student or someone who's interested in coding, I want to know how can I
>   apply for digitalents program. There is a button link to application form of
>   digitalents program at the bottom of `digitalents` page.

- HTML Add a section with a `<h3>` and 4 `<div>` to display the advantages.

- CSS Use `display:flex` to display the advantages `<div>` as 2 x 2 blocks.

## About

> - As a user, I want to know the core values of HYF. There is a banner with all
>   the HYF core values listed `about` page.

- HTML Add a section on the top of `about` page, add 5 `<div>` with `<img>` and
  `<h3>` text .

- CSS Use `display:flex` to display the core values as 1 x 5 blocks.

> - As a user, I want to know the team members of HYF. There is a introduction
>   of HYF core members on `about` page.\_

- HTML Add a section with 3 main `<div>` include `<img>`, `<h3>`, `<p>` and 2
  `<a>` include `<img>`.

- CSS

`<div>`

1. box-shadow: rgba(0, 0, 0, 0.1) 5px 4px 8px 5px;
2. padding: 20px 40px;
3. border-radius: 7px;

`<img>`

1. width: 180px;
2. height: 180px;
3. object-fit: cover;
4. border-radius: 100%;
5. filter: grayscale(1);

## FAQ

> - As a potential student/volunteer/partner, I want to know find the answers of
>   some common questions. There is a blocks of answers of some common questions
>   about student/volunteer/partner on `FAQ` page.

- HTML Add a `FAQ` page link in the navbar of index.html.

> - As a potential student/volunteer/partner, I want to know find the answers of
>   some common questions. There is a blocks of answers of some common questions
>   about student/volunteer/partner on `FAQ` page.

- HTML Add a search `<input>` on the top left of the page.

- CSS Use the following properties to style the `<input>`:

1. flex-grow: 1;
2. border: none;
3. padding: 12px 10px;
4. color: rgb(74, 80, 187);.

## Support us

<<<<<<< HEAD
>>>>>>> 772d233 (update backlog)
=======
> - As a potential partner, I want to know why should I support HYF and what are
>   the advantages. There is a introduction text to invite people or companies
>   to be the partners of HYF on the top of `support us` page.

- HTML Add a `support us` page link in the navbar of index.html, with `<p>` for
  intro text and `<a>` for contact link.

> - As a user, I want to support HYF by donating money. There is a donation form
>   on `support us` page.

- HTML Add a `<section>`with a `<form>` donation form. Use `<ul>`,`<li>` to list
  out the amount that visitors want to donate. Add `<input>` to allow visitors
  modify the amount oof donation or leave a message.

- CSS When hover, the button of amount become:

1. background-color: rgb(28, 34, 148);
2. color: white;
>>>>>>> ae916f3 (update)

​
