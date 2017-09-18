created by kusob

boseokjung@gmail.com

![Alt text](./img.png?raw=true "Title")

import SelectBox from "./selectBox";


<SelectBox

  list={[1,2,3]} //selectBox list, array or object array

  selectBoxText={null}
  
    //if your list is object, selectBoxText's value == something print Variable in the object.
    
    // ex) obj={id,:1, name:"boseok"} than selectBoxText="name" (variable name)
/>


<SelectBox 
    
    list={[{id:1, name:"boseok1"},{id:2, name:"boseok2"}]}
    
    //Array or [Object]
    
    currentItem={1} //selected "boseok2", currentItem={0} will select "boseok1"
    
    selectBoxText="name" // <= this will show your list.name on selectBox list
    
    selectStyle={{styles}}
    
    optionStyle={{styles}}
    
    fontSize={15} //default == 17
    
    icon="text" //default == ▼
    
    onClickBoxFunction={(i)=>{ //i==index
    
        //some function for onSelect
    
    }}

/>

