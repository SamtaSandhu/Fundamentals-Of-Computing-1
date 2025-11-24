# Fundamentals-Of-Computing-1
# 📊 Data Structure Visualizer - CMPS1134 Final Project

 

> An interactive web-based educational tool that visualizes Stack (LIFO) and Queue (FIFO) data structures with real-time animations and operations.

## 🎯 Project Overview

This project is the final deliverable for **CMPS1134 - Fundamentals of Computing** at the University of Belize. Our team created a comprehensive web portfolio featuring an interactive Data Structure Visualizer that demonstrates fundamental computer science concepts through visual, hands-on learning.

### ✨ Key Features

- **Interactive Stack Visualization** - Push and pop operations with LIFO (Last In First Out) behavior
- **Interactive Queue Visualization** - Enqueue and dequeue operations with FIFO (First In First Out) behavior
- **Real-time Animations** - Smooth transitions showing data structure operations
- **Professional Portfolio Website** - Team profiles, video demonstrations, and documentation
- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI/UX** - Luxury black and gold design aesthetic with intuitive controls

## 🚀 Live Demo

**Visit the live website:**  https://samtasandhu.github.io/Fundamentals-Of-Computing-1/ 
## 👥 Team Members

| Name 
|------|
| **Samta Sandhu**  |
| **Jabez Jou** |
| **Albert Gilharry**| 
| **Jamilah Usher** |  

## 🛠️ Technologies Used

- **HTML5** - Semantic markup and structure
- **CSS3** - Styling, animations, and responsive design
- **JavaScript (ES6)** - Interactive functionality and data structure logic
- **GitHub Pages** - Free web hosting and deployment
- **Google Drive** - Video hosting and document storage

## 📂 Project Structure

```
team2-foc-project/
├── index.html              # Main portfolio website
├── visualizer.html         # Data structure visualizer application
├── README.md              # This file
├── samta.jpg              # Team member photo
├── jabez.jpg              # Team member photo
└── jamilah.jpg            # Team member photo
```

## 🎓 Educational Value

This visualizer helps students understand:

- **Stack Operations**: Push (add to top) and Pop (remove from top)
- **Queue Operations**: Enqueue (add to rear) and Dequeue (remove from front)
- **LIFO vs FIFO**: Visual comparison of different data structure behaviors
- **Real-world Applications**: Browser history (Stack), Print queues (Queue)
- **Time Complexity**: O(1) operations for all stack and queue functions

## 💻 How to Use the Visualizer

### Stack Mode (LIFO)
1. Click the **"STACK (LIFO)"** button
2. Enter a value in the input field
3. Click **"PUSH"** to add an element to the top
4. Click **"POP"** to remove the top element
5. Observe the vertical stack visualization with TOP pointer

### Queue Mode (FIFO)
1. Click the **"QUEUE (FIFO)"** button
2. Enter a value in the input field
3. Click **"PUSH"** to add an element to the rear
4. Click **"POP"** to remove the front element
5. Observe the horizontal queue visualization with FRONT and REAR pointers

## 🔧 Local Development

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, or Edge)
- Text editor (VS Code recommended)
- Git installed on your system

### Installation Steps

1. **Clone the repository**
```bash
git clone https://github.com/SamtaSandhu/Fundamentals-of-computng-semester-project-..git
```

2. **Navigate to the project directory**
```bash
cd team2-foc-project
```

3. **Open in your browser**
```bash
# On macOS
open index.html

# On Windows
start index.html

# On Linux
xdg-open index.html
```

### Using Live Server (Recommended)

1. Install [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) VS Code extension
2. Right-click on `index.html`
3. Select "Open with Live Server"
4. Website opens at `http://localhost:5500`

## 🚀 Deployment

This project is deployed using **GitHub Pages**. To deploy your own version:

1. **Push code to GitHub**
```bash
git add .
git commit -m "Initial commit"
git push origin main
```

2. **Enable GitHub Pages**
   - Go to repository Settings
   - Navigate to Pages section
   - Select branch: `main`
   - Select folder: `/ (root)`
   - Click Save

3. **Access your site**
   - URL: `https://github.com/SamtaSandhu/Fundamentals-of-computng-semester-project-..git`
   - Wait 2-5 minutes for deployment

## 📚 Code Documentation

### Stack Implementation

```javascript
// Push operation - O(1) time complexity
function pushToStack(value) {
    stack.push(value);  // Add to end of array (top of stack)
    updateVisualization();
}

// Pop operation - O(1) time complexity
function popFromStack() {
    stack.pop();  // Remove from end of array (top of stack)
    updateVisualization();
}
```

### Queue Implementation

```javascript
// Enqueue operation - O(1) time complexity
function enqueueToQueue(value) {
    queue.push(value);  // Add to rear of queue
    updateVisualization();
}

// Dequeue operation - O(n) time complexity (for educational purposes)
function dequeueFromQueue() {
    queue.shift();  // Remove from front of queue
    updateVisualization();
}
```

## 🎨 Design Features

- **Color Scheme**: Professional black (#1a1a1a) and gold (#d4af37)
- **Typography**: Segoe UI for clean, modern look
- **Animations**: CSS keyframes for smooth element transitions
- **Responsive**: Mobile-first design with CSS Grid and Flexbox
- **Accessibility**: Semantic HTML and proper ARIA labels

## 📖 Learning Outcomes

Through this project, our team gained experience in:

✅ **Web Development**: HTML, CSS, JavaScript fundamentals  
✅ **Data Structures**: Practical implementation of Stacks and Queues  
✅ **Version Control**: Git and GitHub workflows  
✅ **Collaboration**: Team coordination and code integration  
✅ **UI/UX Design**: Creating intuitive user interfaces  
✅ **Problem Solving**: Debugging and optimization  
✅ **Documentation**: Technical writing and README creation  

## 🐛 Known Issues

- Queue dequeue uses `shift()` which has O(n) complexity (acceptable for educational purposes)
- Mobile landscape mode may require horizontal scrolling for queue visualization
- Browser storage not implemented (data clears on page refresh)

## 🔮 Future Enhancements

- [ ] Add Peek operation to view top/front element without removing
- [ ] Implement additional data structures (Linked Lists, Trees, Graphs)
- [ ] Add step-by-step animation controls
- [ ] Display code snippets alongside visualizations
- [ ] Add dark/light theme toggle
- [ ] Implement local storage to persist data
- [ ] Add sound effects for operations
- [ ] Create tutorial mode for beginners

## 📄 License

This project is created for educational purposes as part of CMPS1134 coursework at the University of Belize. All rights reserved by the team members.

## 🙏 Acknowledgments

- **Course Instructor**: LLOYD AUGUSTINE - for guidance and teaching
- **University of Belize** - Faculty of Science and Technology
- **CMPS1134 Course Materials** - Lecture notes on Data Structures and Algorithms
- **MDN Web Docs** - For comprehensive web development resources
- **GitHub Pages** - For free hosting services

## 📞 Contact

For questions or feedback about this project:

- **Samta Sandhu** - [2025162613@ub.edu.bz]
 

## 🔗 Links

- **Live Website**: [https://github.com/SamtaSandhu/Fundamentals-of-computng-semester-project-..git](https://github.com/SamtaSandhu/Fundamentals-of-computng-semester-project-..git)
- **Project Report**: [Google Drive Link]
- **Presentation Slides**: [Google Drive Link]
- **Video Demonstrations**: Available on the website

---

### 📊 Project Statistics

![Lines of Code](https://img.shields.io/badge/Lines%20of%20Code-2000+-blue)
![Files](https://img.shields.io/badge/Files-6-green)
![Last Commit](https://img.shields.io/github/last-commit/SamtaSandhu/team2-foc-project)

### ⭐ Star This Repository

If you found this project helpful or interesting, please consider giving it a star! ⭐

---

**Made with ❤️ by Team 2 - CMPS1134 Final Project**
