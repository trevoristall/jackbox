# Jackbox
Display timed notifications easy


![Preview](https://github.com/ja1984/jackbox/blob/master/preview.gif)


##### Getting started is easy

```javascript
<script>
    Jackbox.init();
</script>
```

##### Adding notifications is just as easy
```javascript
<script>
    Jackbox.error("Oh noes, something went wrong!");

    Jackbox.warning("Yeah, you might want to check in to that");

    Jackbox.success("Woop woop!");

    Jackbox.information("I'm only here because I can");
</script>
```

##### Customization is a breeze
```javascript
<script>
    var customSettings = {
        notification: {
            time : 10, //in seconds, default is set to 5
            classNames : "custom-class-name" //can be multiple
        }
    }
    Jackbox.init(customSettings);
</script>
```
