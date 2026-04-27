# Build Instructions for Electron App

## Prerequisites
1. **Node.js**: Ensure that Node.js is installed on your system. You can download it from the [official website](https://nodejs.org/).
2. **npm**: npm (Node Package Manager) comes bundled with Node.js, but you can also install it separately if needed.

## Steps to Build the Electron App into an EXE File for Windows

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/CodeByShift/fictional-rotary-phone.git
   cd fictional-rotary-phone
   ```

2. **Install Dependencies**:
   Run the following command to install all required packages:
   ```bash
   npm install
   ```

3. **Build the Application**:
   After the installation is complete, build the application by running:
   ```bash
   npm run build
   ```

4. **Create the EXE File**:
   If the previous command ran successfully, the EXE file will be created in the `dist` folder or a similar output folder as defined in your `package.json` file.

5. **Run the Application**:
   Navigate to the output folder and run the EXE file to test the application.

## Additional Notes
- Ensure all dependencies are compatible with your version of Node.js.
- If you encounter any issues, refer to the project's README or the documentation of the dependencies used in the project.

## Troubleshooting
- Check for common issues related to dependency installations or build process errors on the Electron [GitHub page](https://github.com/electron/electron).

Feel free to reach out to the maintainers for further assistance if required.