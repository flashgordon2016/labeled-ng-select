# labeled-ng-select
Angular select, multi-select, and autocomplete component built on ng-select with built-in labels and error feedback.

## Usage
Define options in your consuming component:
```js
@Component({...})
export class ExampleComponent {
  control = new FormControl();

  bikes: [
    { id: 1, name: 'Schwinn'},
    { id: 2, name: 'Giant' },
  ];
}
```
In the template use `labeled-ng-select` component with your options:
```html
<labeled-ng-select [formControl]="control" label="Bike"></labeled-ng-select>
```

