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
  ` rgb(28, 34, 148)` . The job title is color `#4A50BB` . All text are
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
