<img src="demo.gif" width="350px" alt="Demo">

<strong>How to use</strong><br>
```html
<div class="form-group">
  <app-toggle>
    label="Premium Features Enabling"
    [checked]="isPremium"
    (checkedChanged)="isPremium = $event"
    [disabled]="false">
  </>
</div>
```
I recommend to envelop it with a form group container.
