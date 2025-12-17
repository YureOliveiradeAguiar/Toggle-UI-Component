<img src="demo.gif" width="350px" alt="Demo" style="border-radius: '8px'">
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
Recommended to used enveloped by a form group container.
