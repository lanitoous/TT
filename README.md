<!DOCTYPE html>
 <html lang="ko">
 <head>
   <meta charset="UTF-8">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>변하는 이미지</title>
   <style>
     .image-container {
       position: relative;
       width: 300px;
       height: 600px;
     }
     .image-container img {
       position: absolute;
       width: 100%;
       height: 100%;
       object-fit: cover;
       transition: opacity 0.3s ease-in-out;
     }
     .image-container .hover-image {
       opacity: 0;
     }
     .image-container:hover .hover-image {
       opacity: 1;
     }
     .image-container:hover .default-image {
       opacity: 0;
     }
   </style>
 </head>
 <body>
   <div class="image-container">
     <img class="default-image" src="https://file.notion.so/f/f/8e89d478-d276-4d7c-b7e1-34648bb70ee0/886e1f24-4990-4820-a231-d67d48f4e80a/r79.png?table=block&id=1c8300a2-d731-80b0-bcb9-df9770ec5e2a&spaceId=8e89d478-d276-4d7c-b7e1-34648bb70ee0&expirationTimestamp=1743537600000&signature=WNnuPuWqdHKMsGyIxfRNMRlhKVv4bbcG0-0SUgsDC6c&downloadName=r79.png" alt="기본 이미지">
     <img class="hover-image" src="https://file.notion.so/f/f/8e89d478-d276-4d7c-b7e1-34648bb70ee0/acff0cbd-e524-4e43-90e1-79be934cf69f/r79.0.png?table=block&id=1c8300a2-d731-80dc-8546-e124a7fe0822&spaceId=8e89d478-d276-4d7c-b7e1-34648bb70ee0&expirationTimestamp=1743537600000&signature=J-eOzU5zRuqsrbAs-d-lebuDCfPiF-Ev0rlepauX1_I&downloadName=r79.0.png" alt="호버 이미지">
   </div>
 </body>
 </html>
 

