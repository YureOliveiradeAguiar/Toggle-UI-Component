<div class="form-group"> <br>
  <app-toggle<br>
    label="Premium Features Enabling"<br>
    [checked]="isPremium"<br>
    (checkedChanged)="isPremium = $event"<br>
    [disabled]="false"><br>
  </app-toggle><br>
</div><br>
<br>
Recommended to used enveloped by a form group container.
