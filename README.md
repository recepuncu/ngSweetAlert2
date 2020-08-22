# AngularJS wrapper for SweetAlert2

AngularJS wrapper for [SweetAlert2](https://sweetalert2.js.org/). Sweet Alert is a beautiful replacement for Javascript's "Alert".

## Usage
```sh
SweetAlert2.fire({
  title: 'Are you sure?',
  text: "You won't be able to revert this!",
  icon: 'warning',
  showCancelButton: true,
  confirmButtonColor: '#3085d6',
  cancelButtonColor: '#d33',
  confirmButtonText: 'Yes, delete it!'
}).then((result) => {
  if (result.value) {
    SweetAlert2.fire(
      'Deleted!',
      'Your file has been deleted.',
      'success'
    )
  }
})
```

## Demo
[http://recepuncu.github.io/ngSweetAlert2/](http://recepuncu.github.io/ngSweetAlert2/)

## Dependencies
- required:  
	[AngularJS](https://github.com/angular/angular)  
	[sweetalert2](https://github.com/sweetalert2/sweetalert2)

## Install
1. download the files
	1. Bower
		1. add `"angularjs-sweetalert2": "latest"` to your `bower.json` file then run `bower install` OR run `bower install angularjs-sweetalert2`
	2. npm
		1. add `"angularjs-sweetalert2": "latest"` to your `package.json` file then run `npm update` OR run `npm i angularjs-sweetalert2`
2. include the files in your app
	1. `SweetAlert2.min.js`
	2. `sweetalert2.min.js"`
	3. `sweetalert2.min.css`
3. include the module in angular (i.e. in `app.js`) - `recepuncu.ngSweetAlert2`


## Documentation

- [http://recepuncu.github.io/ngSweetAlert2/](http://recepuncu.github.io/ngSweetAlert2/)
