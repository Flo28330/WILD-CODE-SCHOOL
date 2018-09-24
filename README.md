
//Tranformer du code JavaScript en code TypeScript

function hello (name:string) {
    console.log("Hello " + name);
}

const firstName:string = "bob";
hello(firstName);
hello(firstName + " marley");

function concat(a,b) {
    return a + b;
}

const wcs = concat("Wild",concat("Code", "School"));
console.log(wcs);
