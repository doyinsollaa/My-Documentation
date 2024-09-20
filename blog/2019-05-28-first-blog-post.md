---
slug: first-blog-post
title: First Blog Post
authors: [slorber, yangshun]
tags: [hola, docusaurus]
---

Lorem ipsum dolor sit amet...

<!-- truncate -->

...consectetur adipiscing elit. Pellentesque elementum dignissim ultricies. Fusce rhoncus ipsum tempor eros aliquam consequat. Lorem ipsum dolor sit amet

import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';

<Tabs> 
    <TabItem value="book" label="Book" default>
       Dive into the world of knowledge with a captivating book &#128218; 
    </TabItem>
    <TabItem value="painting" label="Painting">
       Amire the strokes of artistry on a beautiful painting🌆  
    </TabItem>
    <TabItem value="music" label="Music">
       Let the smoothing melodies of music transport you🎶
    </TabItem>
</Tabs> 

Lorem ipsum dolor amet, consectetur adipiscing elit. Sed non risus. Suspendisse lectus tortor, dignissim sit amet, adipiscing nec, ultricies sed, dolor

```jsx title="Line Numbers with Highlight" {4,9-11} showLineNumbers
import React from 'react';

function UserProfile(props) {
    const { username, email, isAdmin } = props;

    return (
        <div> 
           <h1>User Profile</h1>
           <p>Username: {username}</p>
           <p>Email: {email}</p>
           {isAdmin && <p>Admin User</p>}
        </div>
    );
}
export default UserProfile;
```

Lorem ipsum dolor amet, consectetur adipiscing elit. Sed non risus. Suspendisse lectus tortor, dignissim sit amet, adipiscing nec, ultricies sed, dolor

:::caution

Please take **extre caution** with this important note.

:::