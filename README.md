1.Data binding
Data binding is the core concept of Angular 8 and used to define the communication between a component and the DOM.
One-way databinding
Two-way databinding

2.Input and Output decorators

@Input — Property Binding

If you want to pass data from the parent component to the child component, you need to use two things: @Input and property binding.

@Output & EventEmitter — Event Binding

With @Output and EventEmitter it’s the other way around. You can pass data back from the child to the parent component. Again, we declare a variable in the child, but this time with the@Output decorator and a new EventEmitter:

@ViewChild & AfterViewInit

The third way to pass data is by using @ViewChild and AfterViewInit. With this final option, we can refer to a child component and access their variables inside our parent component.

