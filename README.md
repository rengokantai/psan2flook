#### psan2flook
######filters
```
{{story | json}}
```
bootstrap code
```
import { bootstrap } from 'angular2/platform/browser';
import { AppComponent } from './app.component';

bootstrap(AppComponent)
  .then(success => console.log(`Bootstrap success`))
  .catch(error => console.log(error));
```
######property binding
[see here](http://a2-first-look.azurewebsites.net/examples/a1-a2/a2/property-binding/plnkr.demo.html?bust=1465410501594)



#####cp5
```
[attr.aria-label]="selectLl"
```
capitalize pipe , custom filter
```
@Pipe({name:'initCaps'})
