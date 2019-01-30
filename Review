import React from 'react'
    
    class CoderPad extends React.Component{
    
    render(){
         <Filters/>
        <Reviews updateFilter={filterList} reviewsList="listfromjson"/>
  }
  
}

class Filter extends React.Component{
  
  
  updateFilter(event){
    
    this.setState({value:event.target.value})
   this.props.updateFilter(this.state.value) 
  }
  
 render(){ 
  <select onChange= {this.updateFilter}>  
    
    <options value ="1">   
      /// so on
    </select> 
 }
  
}


///review components

class Reviews extends React.Component{
  constructor(props){
    
   super(props); 
    this.list = props.reviewsList
    this.filteredList = this.state.list
    
  }
  
  filterList(filterValue){
     this.filteredList = this.list.filter(e=>{
       
      
        return e.includes(filterValue)
       
     })
    
  }
 render(){
   
  <ul>
    list.map(element=>{  <li>
        element.title <input /> 
      <p>element.age</p>
                       <p> element.gender  </p>
                        .....//so on
                       <ul> element.tips.map(tip=>{ <li>tip.value</li>  } )  </ul>  
          </li>  })
    </ul>
   
 }
}
