# Hooks

1. useState

import React, { useState } from 'react' 

export default function App () {
  const [resourceType, setResourceType] = useState('posts')
  
  return (
    <> 
      <div> 
        <button onClick={() => setResourceType('posts')}> Posts </button>
        <button onClick={() => setResourceType('users')}> Users </button>
        <button onClick={() => setResourceType('comments')}> Comments </button>
      </div>
    </>
  )
}


        
