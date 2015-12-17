

```
       .-.         MIT Licensed.
      |_:_|
     /(_Y_)\            Original code belongs to T.J.
    ( \/M\/ )     Couldn’t find the code in npm,
  _.'-/'-'\-'._      hence I published under a new name.
 /.--'[[][]'--.\      I’ll create a proper README and stuff
                          when I have time.
                       Until then…
                May the source be with you.
```

## Usage Example

```javascript
import chart from 'darth';
import clear from 'clear';

let data = [];

for ( i = 0; i < 100; i++ ) {
    data.push( Math.random() * 100 );
}

setInterval( () => {
    data.push( Math.random() * 100 );

    clear();
    chart( data );
}, 1000 );
```

// TODO: add a screenshot of the output.
