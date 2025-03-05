# **Procedure & How It Works**  

## 1. Download the Binary File (Release)  
- Obtain the compiled executable from the provided source.  
- Ensure that the file is intact and ready for analysis.  

## 2. Reverse Engineering with Ghidra  
- Load the binary into **Ghidra**, a powerful reverse engineering tool.  
- Analyze the decompiled code to understand its logic and security mechanisms.  

## 3. Extracting or Modifying the Password Check  
- Locate the function responsible for password validation.  
- Either:  
  - Retrieve the original password directly.  
  - Modify the function to accept any **32-character string** and return the password.  
- Apply the necessary modifications to the binary logic.  

## 4. Testing the Modified Binary  
- Run the updated version of the executable to ensure that the logic changes are effective.  
- Validate the extracted or bypassed authentication mechanism.  

---

# **Findings**  

After analyzing and modifying the binary, the following flag was successfully retrieved:  
gdsc{unp4ck1n6_b1n4r135_15_n4u6h7y}
