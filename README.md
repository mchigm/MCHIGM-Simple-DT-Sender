# MCHIGM-Simple-DT-Sender

This repository focuses on achieving/archiving simple ways to send data from Peer to Peer.

## 📖 About

This project serves as both a reference implementation and a community hub for different approaches to peer-to-peer data transfer. We welcome contributions from developers who want to share their own implementations and solutions.

## 🌳 Repository Structure

This repository uses a two-branch workflow:

- **`Original`** - Contains the repository's source code and reference implementation
- **`Main`** - Holds community-contributed code and variations

## 🤝 Contributing

We welcome community contributions! You can submit your own version or variation of the peer-to-peer data sender.

### How to Contribute

1. **Fork this repository**

2. **Create your implementation**
   - Develop your own version of the data transfer solution
   - Add your code files to your fork

3. **Create a Pull Request to the `main` branch**
   - Important: Your PR title must follow this exact format:
     ```
     (Your Name) | (Project Name)
     ```
   - Example: `(Jane Smith) | (WebSocket Data Sender)`
   - Example: `(John Doe) | (UDP Fast Transfer)`

4. **Automated Organization**
   - Once you create the PR, our GitHub Action will automatically:
     - Validate your PR title format
     - Check if a folder with your name exists
     - Create a folder named after you if it doesn't exist
     - Move your contributed files into your folder
     - Create a README template for your project (if new folder)

5. **Update Your Project README**
   - After the automation runs, update the README in your folder with:
     - Project description
     - Usage instructions
     - Any dependencies or requirements
     - Examples

6. **Review and Merge**
   - Once everything looks good, your PR will be reviewed and merged

### PR Title Format Requirements

❌ **Invalid formats:**
- `My awesome project`
- `John Doe - My Project`
- `(John Doe) (My Project)`

✅ **Valid format:**
- `(John Doe) | (My Awesome Project)`

### What Happens Automatically

When you submit a PR with the correct title format, the GitHub Action will:

1. Parse your name and project name from the PR title
2. Create a folder with your name (e.g., `John_Doe/`) if it doesn't exist
3. Move all your contributed files into your folder
4. Generate a starter README for your project
5. Commit and push the organized structure back to your PR branch
6. Add a comment confirming the organization

### File Organization

Your folder structure will look like:

```
main/
├── John_Doe/
│   ├── README.md
│   ├── your-file-1.py
│   ├── your-file-2.js
│   └── ...
├── Jane_Smith/
│   ├── README.md
│   ├── her-implementation.go
│   └── ...
└── ...
```

## 📋 Examples

### Example Contribution Workflow

1. Fork the repository
2. Add your files (e.g., `my_sender.py`, `config.json`)
3. Create a PR to `main` branch with title: `(Alex Johnson) | (Python P2P Sender)`
4. The action runs and organizes files into `Alex_Johnson/` folder
5. Update `Alex_Johnson/README.md` with your project details
6. PR gets reviewed and merged

## 🎯 Project Goals

- Provide a reference implementation for P2P data transfer
- Build a community collection of different approaches and solutions
- Learn from each other's implementations
- Support multiple programming languages and frameworks

## 📝 License

Please ensure your contributions comply with the repository's license and do not include proprietary or sensitive code.

## 🐛 Issues

If you encounter any issues with the automated workflow or have questions, please open an issue in this repository.

---

**Happy Contributing! 🚀**