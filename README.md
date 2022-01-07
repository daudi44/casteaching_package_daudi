# Install

```bash
npm install @daudi/casteachingdani
```

# Usage

```javascript
import casteaching from 'casteaching'

// Obtain published video list
casteaching.videos()

// Obtain video by id
casteaching.video.show(1)

// Create Video
casteaching.video.create({name: 'One Video Testing', description: 'Hello There',  url: 'somewebvideopage.com' })

// Update Video
casteaching.video.update(1,{name: 'First Video Testing', description: 'Hello There Boys and Girls',  url: 'somewebvideopage.com' })

// Destroy Video
casteaching.video.destroy(1)
```

# Author & Project Info

- Daniel Audí Bielsa
- Github Casteaching global project: https://github.com/daudi44/casteaching/tree/api
- Github Package: https://github.com/daudi44/casteaching_package_daudi#readme
