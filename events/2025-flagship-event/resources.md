# GDG WOW Pune 2025 Flagship Event Resources

This directory contains materials and resources from our 2025 flagship event.

## Presentation Slides

- [Welcome and Introduction](https://gdg-wow-pune-resources.example/slides/welcome-2025.pdf)
- [Getting Started with AI/ML Workshop](https://gdg-wow-pune-resources.example/slides/ai-ml-workshop.pdf)
- [Web Development with Modern Frameworks](https://gdg-wow-pune-resources.example/slides/web-dev-frameworks.pdf)
- [Cloud Computing Fundamentals](https://gdg-wow-pune-resources.example/slides/cloud-computing.pdf)
- [Breaking Barriers in Tech Panel](https://gdg-wow-pune-resources.example/slides/panel-discussion.pdf)
- [Kotlin for Android Development](https://gdg-wow-pune-resources.example/slides/kotlin-android.pdf)
- [Open Source Contribution for Beginners](https://gdg-wow-pune-resources.example/slides/open-source.pdf)
- [Innovation for Impact Keynote](https://gdg-wow-pune-resources.example/slides/keynote.pdf)

## Workshop Code Samples

### AI/ML Workshop

```python
# Simple TensorFlow example from the workshop
import tensorflow as tf
import numpy as np

# Create a simple dataset
x = np.array([-1.0, 0.0, 1.0, 2.0, 3.0, 4.0], dtype=float)
y = np.array([-3.0, -1.0, 1.0, 3.0, 5.0, 7.0], dtype=float)

# Create and train a model
model = tf.keras.Sequential([
    tf.keras.layers.Dense(1)
])
model.compile(loss='mean_squared_error',
              optimizer=tf.keras.optimizers.Adam(0.1))
model.fit(x, y, epochs=100, verbose=0)

# Make a prediction
print(model.predict([10.0]))
```

### Web Development Workshop

```javascript
// React component example from the workshop
import React, { useState } from 'react';

function Counter() {
  const [count, setCount] = useState(0);
  
  return (
    <div className="counter">
      <h2>Counter: {count}</h2>
      <button onClick={() => setCount(count + 1)}>
        Increment
      </button>
      <button onClick={() => setCount(count - 1)}>
        Decrement
      </button>
    </div>
  );
}

export default Counter;
```

### Kotlin Android Workshop

```kotlin
// Simple Kotlin Android example from the workshop
class MainActivity : AppCompatActivity() {
    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        setContentView(R.layout.activity_main)
        
        val button = findViewById<Button>(R.id.button)
        val textView = findViewById<TextView>(R.id.textView)
        
        button.setOnClickListener {
            textView.text = "Hello, GDG WOW Pune!"
        }
    }
}
```

## Additional Resources

- [Speaker Contact Information](https://gdg-wow-pune-resources.example/speakers.pdf)
- [Recommended Learning Paths](https://gdg-wow-pune-resources.example/learning-paths.pdf)
- [Community Projects](https://gdg-wow-pune-resources.example/community-projects.pdf)
- [Event Photos](https://gdg-wow-pune-resources.example/photos/)

## Feedback and Follow-up

If you attended the event, please fill out our [feedback form](https://gdg-wow-pune-resources.example/feedback) to help us improve future events.

For questions or collaborations that arose from the event, contact us at: contact@gdgwowpune.example.com