# Project Related to DOM

## project link
[click here] (https://ornate-beijinho-13b823.netlify.app/)
# Solution Code

## project 1

```javascript
console.log("vaibhav")
const btn = document.querySelectorAll('.button')
        // console.log(btn)
        const body = document.body
        // console.log(body)

        btn.forEach((button) => {
            // console.log(btn)
            button.addEventListener('click', function (e) {
                // console.log(e)
                // console.log(e.target)

                switch (e.target.id) {
                    case 'green':
                        // console.log(e.target.id)
                        body.style.backgroundColor = e.target.id
                        break;
                    case 'grey':
                        // console.log(e.target.id)
                        body.style.backgroundColor = e.target.id
                        break;
                    case 'pink':
                        // console.log(e.target.id)
                        body.style.backgroundColor = e.target.id
                        break;
                    case 'blue':
                        // console.log(e.target.id)
                        body.style.backgroundColor = e.target.id
                        break;
                    case 'yellow':
                        // console.log(e.target.id)
                        body.style.backgroundColor = e.target.id
                        break;
                    case 'red':
                        // console.log(e.target.id)
                        body.style.backgroundColor = e.target.id
                        break;


                    default:
                        console.log("Oops... Not found ")
                        break;
                }
            })
        })

```

## Updated Code

```javascript
const btn = document.querySelectorAll(".color-button");
        // console.log("object")
        // console.log(btn);
        const body = document.body;
        btn.forEach((button) => {
            // console.log(button)
            // console.log(btn) Return NodeListp[]
            button.addEventListener('click', function (e) {
                // console.log(e)
                // console.log(e.target)
                console.log(e.target.id)
                body.style.backgroundColor = e.target.id

            })
        })

```



