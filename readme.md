## Sign in

Sign in template.

## Installation

```
npm install --save css-ui-sign-in
```

## Demo

- https://css-ui.github.io/sign.in

## Quick start

CSS dependencies.

```html
<link rel="stylesheet" href="path/to/normalize.css">
<link rel="stylesheet" href="path/to/open-sans.css">
<link rel="stylesheet" href="path/to/cssui.css">
```

CSS sing in style.

```html
<link rel="stylesheet" href="path/to/style.sign.in.css">
```

Set font.

```html
<style>
	body {
		font-family: 'Open Sans', sans-serif;
	}
</style>
```

Sign in html.

```html
<div class="container box">

	<!-- avatar -->
	<div class="align center">
		<img src="path/to/avatar.png" alt="avatar" class="sign-gravatar">
	</div>

	<!-- welcome message -->
	<div class="align center">
		<h1>Welcome!</h1>
		<p>Sign in to your account.</p>
	</div>

	<!-- sign in form -->
	<div class="sign in">
		<form class="group">
			<input type="email" placeholder="E-mail" required class="unite first full width">
			<input type="password" placeholder="Password" required class="unite last full width">
			<div class="align right">
				<input type="submit" value="Sign in" class="button primary">
			</div>
		</form>
	</div>
</div>

<!-- footer -->
<div class="bottom footer">
	<p class="align center">&copy; CSS UI</p>
</div>
```

Enjoy the sign in template.
