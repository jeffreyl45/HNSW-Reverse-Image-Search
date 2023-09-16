# Similar Image Search
<h2>Description:</h2>
- An application that searches for the top 5 visually similar images from an updatable HNSW database to a user's input image via URL <br/>
- Training images from: http://host.robots.ox.ac.uk/pascal/VOC/voc2012/VOCtrainval_11-May-2012.tar <br/>
- Note: This application is designed to run on Jupyter Notebook: https://jupyter.org/<br/>
<h2>Running Instructions:</h2>
1. Download and untar http://host.robots.ox.ac.uk/pascal/VOC/voc2012/VOCtrainval_11-May-2012.tar <br/>
2. Copy the VOCdevkit/VOC2012/JPEGImages folder into the same directory as imageSearch.ipynb <br/>
3. Upload more jpg or JPEG in the image folder (optional)<br/>
4. Run the first code block and wait for the database to be saved <br/>
5. Change the URL of the image where specified in the second code block (optional)<br/>
6. Run the second code block to see the results<br/>
7. The database and its index are imageDB and imageDB.dat respectively, delete these if you want to start over <br/>
<h2>Demonstration Video</h2>
Google Drive Link: https://drive.google.com/file/d/187OAVhClP7duH0WZroJ5XjD0vYqtp-Dn/view?usp=sharing
