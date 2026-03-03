# File System Explorer 📁

A comprehensive C# console application demonstrating four fundamental data structures working together in a real-world scenario.

## 🎯 Purpose

This project was created to deeply understand how different data structures can work together in a practical application. It simulates a file system while demonstrating:

- **🌳 Tree Structure** - Directory hierarchy
- **🔗 Doubly Linked List** - Files within directories  
- **📚 Stack (LIFO)** - Navigation history
- **⏱️ Queue (FIFO)** - Recent items

## 🏗️ Architecture

### Data Structures Implemented

#### 1. Tree (Directories)
- Parent-child relationships
- Root directory with nested subdirectories
- Each directory knows its parent and children
- Level tracking for depth

#### 2. Doubly Linked List (Files)
- Each directory maintains its own file list
- Next/Previous pointers for bidirectional traversal
- Head (FirstFile) and Tail (LastFile) pointers
- O(1) insertion at end

#### 3. Stack (Navigation History)
- LIFO behavior for back/forward navigation
- Tracks directory visit order
- Enables "Back" and "Forward" functionality

#### 4. Queue (Recent Items)
- FIFO behavior for recent directories
- Maintains last 5 visited items
- Automatically drops oldest when new ones added

## 🚀 Features

- Create nested directory structures
- Add files to any directory
- Navigate through directories (up/down)
- Track navigation history
- View recent items (last 5)
- Forward/backward file traversal
- Delete files with proper pointer updates
- Search for files
- Display current directory statistics

## 📋 Sample Output

The program provides clear visual output showing:
- Directory creation with levels
- File addition to specific directories
- Stack contents (most recent on top)
- Queue contents (oldest to newest)
- Linked list traversal in both directions
- File deletion and verification

## 🎓 Learning Outcomes

By studying this code, you'll understand:
- How trees model hierarchical data
- How linked lists manage collections with efficient insert/delete
- How stacks provide LIFO access for history
- How queues provide FIFO access for recent items
- How multiple data structures can work together
- Proper C# coding practices with XML comments
- Object-oriented design principles

## 🔧 Requirements

- .NET Core SDK or .NET Framework
- Any C# IDE (Visual Studio, VS Code, Rider)
- Git (for cloning)

## 🏃 Running the Application

```bash
dotnet run
