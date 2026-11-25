# Storage Analysis — Observation Sheet

## Aim
To examine file types, extensions, sizes, directory hierarchy, file properties, and storage capacity, and to understand how the operating system organizes files and tracks storage use.

## Folder hierarchy and example paths
```text
Desktop/
└── Storage_Analysis/
    ├── Documents/
    │   └── notes.txt
    ├── Images/
    │   └── sample_photo.jpg
    └── Media/
        └── sample_audio.mp3
```

Example paths (Windows):
- `C:\\Users\\Student\\Desktop\\Storage_Analysis\\Documents\\notes.txt`
- `C:\\Users\\Student\\Desktop\\Storage_Analysis\\Images\\sample_photo.jpg`
- `C:\\Users\\Student\\Desktop\\Storage_Analysis\\Media\\sample_audio.mp3`

## File properties (illustrative values)

| File name | Extension / type | Example size | Example size on disk |
|---|---|---:|---:|
| notes.txt | TXT / text | 4.2 KB | 4.0 KB |
| sample_photo.jpg | JPG / image | 2.4 MB | 2.4 MB |
| sample_audio.mp3 | MP3 / audio | 5.8 MB | 5.8 MB |

The sample audio is the largest of these examples, and the text file is the smallest. Values are examples only; actual sizes depend on content, compression, file-system allocation units, and metadata.

## Drive storage (illustrative only)

| Measurement | Example |
|---|---:|
| Primary drive | C: SSD |
| Total capacity | 512 GB |
| Used space | 356 GB |
| Free space | 156 GB |

Example major categories:
| Category | Example usage |
|---|---:|
| Apps | 142 GB |
| Other | 89 GB |
| System & reserved | 86 GB |

These numbers are simulated, not readings from the user's computer. Categories can vary by OS and settings.

## File organization observations
- Moving a file between folders on the same drive normally does not change its file contents or logical size; moving across drives can involve copying and deleting and may change allocation.
- Renaming a file while retaining its extension usually does not change its contents or size. The file should open in a compatible application.
- Extensions help identify file formats and the applications likely to open them. They are labels and can be changed without converting the underlying format.
- Hidden files are often used for configuration or system data. Show hidden items cautiously; do not delete unfamiliar system files.
- A directory (folder) stores entries that organize and refer to files and subdirectories. A mount point connects a filesystem to a location in the directory tree (Linux/macOS concepts).
- File size is the logical data length. “Size on disk” may differ due to filesystem allocation units, compression, sparse files, or metadata.

## Relationship between file type, size, directory structure, and storage
Text files often require relatively little space; images and audio/video can occupy more space depending on resolution, duration, encoding, and compression. Folders provide hierarchical organization but do not themselves represent a fixed storage capacity. Filesystems track file metadata and allocated blocks on storage devices. Total capacity is divided among used space and available space (with some filesystem/system reservations possible).

## Result
The exercise demonstrates that file extensions and metadata identify file formats, file size reflects content and encoding, directory hierarchy improves organization, and filesystem storage reports show how capacity is divided between used and free space.

**Submission note:** Replace all illustrative measurements with screenshots or actual readings from your own device if required.
