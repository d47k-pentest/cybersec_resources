<h1 align="Center">Anti-Forensics</h1>

1. Avoiding detection
2. Disrupting collection of information
3. Increasing the time that examiner to spend a case

# Methodology

#### 1. Data Hiding
- Misdirection
    - Renaming file extension
    - Timestomping
- Encryption
    - veracyrpt 
    - sse (android)

#### 2. Data Wiping 

- Bleachbit (For Window and Linux)
- ishradder for Android

#### 3. Encryption

- Cyber-chef

#### 4. Securing Credentialsv

- Bitwarden

#### 5. Stegnography

- download steghide

#### Hiding Data
- `steghide embed -ef '/home/d47k/Desktop/secrets' -cf '/home/d47k/Desktop/d47k_class/photo_with_gps/cat.jpg' -p 12345`

#### Extracting Data

- `steghide extract -sf '/home/d47k/Desktop/d47k_class/photo_with_gps/cat.jpg' -p 12345 -xf /home/d47k/Desktop/extract.txt`