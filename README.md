# Short-Clips-
A website for view, shere , like, and comment and also download the short clips from movie, series, anime etc. This website is mainly for editors  
/* Clip Grid Layout */
.clip-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
    gap: 20px;
    padding: 20px;
}

.clip-card {
    background: #222;
    border-radius: 8px;
    padding: 15px;
    transition: transform 0.3s;
}

.clip-card:hover {
    transform: translateY(-5px);
}

.video-container {
    position: relative;
    padding-bottom: 56.25%; /* 16:9 Aspect Ratio */
    height: 0;
    overflow: hidden;
}

.video-container iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
}

.download-btn {
    display: inline-block;
    margin-top: 10px;
    padding: 8px 15px;
    background: #ff4d4d;
    color: white;
    text-decoration: none;
    border-radius: 4px;
    text-align: center;
}
