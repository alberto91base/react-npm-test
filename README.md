## A small but functional npm package


### Install

`Si estuviese en npm publicado usariamos:`
```sh
npm install react-npm-test
```

`Como solo esta publicado en gitlab usamos`
```
"react-npm-test": "git+https://github.com/alberto91base/react-npm-test#v1.0.1"
```
### Usage 

In a React app, use the Button or Badge components:  
`import { Button } from 'react-npm-test'`
`import { Badge } from 'react-npm-test'`
`import "react-npm-test/dist/components/styles/main.scss"`

#### Button props

| Name        | Description      
| ----------- | -----------      
| kind        | 'Primary' | 'Outline' | 'Inline' | 'Ghost' | ' Warning'            
| data-id     | string             
| type        | 'button' | 'submit' | 'reset'             
| name        | string             
| value       | string             
| disabled    | Boolean          
| onClick     | function         


#### Badge props

| Name        | Description | 
| ----------- | ----------- |
| value       | integer     |
