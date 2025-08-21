# Patterns of Distributed Systems

[![Demo](https://img.shields.io/static/v1?label=Demo&message=Live%20Site&labelColor=2f363d&color=blue&style=flat&logo=github&logoColor=959da5)](https://nickmccarty.me/patterns-of-distributed-systems/)
[![Patterns](https://img.shields.io/badge/Patterns-30-green)](https://nickmccarty.me/patterns-of-distributed-systems/)
[![Categories](https://img.shields.io/badge/Categories-7-orange)](https://nickmccarty.me/patterns-of-distributed-systems/)

> An interactive, visual guide to understanding the fundamental patterns that power modern distributed systems.

## 🎯 What This Is

This project transforms the complex world of distributed systems into an accessible, visual learning experience. Each pattern includes:

- **ASCII Diagrams** - See how the pattern works architecturally
- **Real-World Examples** - Discover which systems use each pattern (Kafka, MongoDB, Cassandra, etc.)
- **Difficulty Levels** - Progress from beginner to advanced concepts
- **Categorized Learning** - Explore patterns by domain (Consensus, Replication, Storage, etc.)
- **Interactive Filtering** - Find exactly what you need to learn

## 🚀 Quick Start

1. **[Visit the Live Demo](https://nickmccarty.me/patterns-of-distributed-systems/)**
2. **Browse by Category** - Use filter buttons to focus on specific domains
3. **Search Patterns** - Type to find patterns by name or technology
4. **Click Any Card** - Deep dive into architecture diagrams and examples
5. **Follow Learning Paths** - Start with beginner patterns and progress upward

## 📚 Pattern Categories

### 🤝 **Consensus** (3 patterns)
Algorithms for nodes to agree on values despite failures
- **Beginner**: None
- **Intermediate**: Majority Quorum, Two-Phase Commit  
- **Advanced**: Paxos

### 🔄 **Replication** (4 patterns)
Keeping data synchronized across multiple nodes
- **Beginner**: Leader and Followers, Follower Reads
- **Intermediate**: High-Water Mark, Replicated Log

### 🗂️ **Partitioning** (2 patterns)
Dividing data across multiple nodes for scalability
- **Beginner**: Fixed Partitions
- **Intermediate**: Key-Range Partitions

### ⏰ **Timing** (5 patterns)
Managing time and ordering in distributed environments
- **Beginner**: Generation Clock
- **Intermediate**: Lamport Clock
- **Advanced**: Clock-Bound Wait, Hybrid Clock, Version Vector

### 📡 **Communication** (7 patterns)
How nodes talk to each other efficiently and reliably
- **Beginner**: HeartBeat, Request Batch, Single-Socket Channel, State Watch
- **Intermediate**: Gossip Dissemination, Idempotent Receiver, Request Pipeline

### 💾 **Storage** (4 patterns)
Persisting and managing data reliably
- **Beginner**: Segmented Log, Versioned Value, Write-Ahead Log
- **Intermediate**: Low-Water Mark

### 🎯 **Coordination** (5 patterns)
Coordinating activities across distributed nodes
- **Beginner**: Emergent Leader, Singular Update Queue
- **Intermediate**: Consistent Core, Lease, Request Waiting List

## 🎓 Learning Paths

### **🌱 Beginner Path**
Start here if you're new to distributed systems:

1. **HeartBeat** - Learn failure detection
2. **Leader and Followers** - Understand basic replication
3. **Write-Ahead Log** - Grasp durability concepts
4. **Fixed Partitions** - See how data is distributed
5. **Generation Clock** - Learn about versioning
6. **Follower Reads** - Understand read scaling
7. Continue with other beginner patterns...

### **🚀 Intermediate Path**
Ready to tackle more complex scenarios:

1. **Majority Quorum** - Learn consensus basics
2. **Lamport Clock** - Understand logical time
3. **Gossip Dissemination** - See epidemic protocols
4. **High-Water Mark** - Grasp replication safety
5. Continue with consensus and coordination patterns...

### **🎯 Advanced Path**
Master the most sophisticated concepts:

1. **Paxos** - The gold standard of consensus
2. **Clock-Bound Wait** - Handle time uncertainty
3. **Hybrid Clock** - Combine physical and logical time
4. **Version Vector** - Detect concurrent updates

## 🛠️ Technologies Highlighted

Implementations across major distributed systems:

| System | Patterns Used |
|--------|---------------|
| **Apache Kafka** | Leader-Followers, High-Water Mark, Segmented Log, Fixed Partitions, Generation Clock |
| **MongoDB** | Majority Quorum, Emergent Leader, Follower Reads, Hybrid Clock |
| **Apache Cassandra** | Gossip Dissemination, Fixed Partitions, Majority Quorum, Paxos |
| **PostgreSQL** | Write-Ahead Log, Leader-Followers |
| **Google Spanner** | Clock-Bound Wait, Paxos |
| **CockroachDB** | Clock-Bound Wait, Hybrid Clock |
| **etcd/Consul** | Raft (Leader-Followers), Lease, State Watch |

## 💡 Use Cases

**👨‍🎓 For Students**
- Visual learning with ASCII diagrams
- Progressive difficulty levels
- Real-world context and examples

**👩‍💻 For Engineers**
- Quick reference during system design
- Find patterns used by specific technologies
- Understand trade-offs and implementation details

**👨‍🏫 For Educators**
- Ready-made visual explanations
- Categorized curriculum structure
- Links to authoritative sources

**🏢 For Teams**
- Shared vocabulary for architecture discussions
- Pattern selection guidance
- Implementation inspiration

## 🔗 Original Source

This interactive guide is based on Martin Fowler's excellent [Patterns of Distributed Systems](https://martinfowler.com/articles/patterns-of-distributed-systems/) series. Each pattern links directly to the detailed article for deeper understanding.

## 🤝 Contributing

Found an issue or want to improve a pattern description?

1. **Fork this repository**
2. **Create a feature branch**: `git checkout -b improve-ascii-diagrams`
3. **Make your changes** to `index.html`
4. **Test locally** by opening the file in your browser
5. **Submit a pull request** with a clear description

### What to Contribute
- **Improved ASCII diagrams** - Make concepts clearer
- **Better real-world examples** - Add systems you know use these patterns
- **Enhanced descriptions** - Clarify complex concepts
- **Additional tags** - Help with discoverability
- **Mobile optimizations** - Improve the mobile experience

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- **Martin Fowler** - For the foundational patterns and explanations
- **Unmesh Joshi** - Co-author of the original patterns series
- **Distributed Systems Community** - For the real-world implementations and insights

---

**⭐ Star this repository** if it helped you understand distributed systems better!

**🔄 Share it** with your team to establish a common vocabulary for distributed systems discussions.

**📖 Keep learning** by exploring the detailed articles linked from each pattern.
