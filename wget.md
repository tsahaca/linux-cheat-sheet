## Recurrsive download
  - wget --no-parent --no-check-certificate -r https://<hostname>/teaching/310/slides/
  - curl -LO http://example.com/
  
### Recurrsive find  
  - Get-ChildItem -Path C:\ -Filter "Scalability Lecture 01 - Types of Scaling.pdf" -Recurse -ErrorAction SilentlyContinue -Force
