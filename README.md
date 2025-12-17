<div class="form-group">
  <app-toggle>
    label="Premium Features Enabling"
    [checked]="isPremium"
    (checkedChanged)="isPremium = $event"
    [disabled]="false">
  </app-toggle>
</div>
Recommended to used enveloped by a form group container.
