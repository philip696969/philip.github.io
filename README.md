/* General Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    color: #333;
    background-color: #f4f4f9;
    margin: 0;
}

.container {
    width: 90%;
    max-width: 1200px;
    margin: auto;
}

header {
    background: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    font-size: 2.5rem;
}

nav {
    background: #444;
    color: #fff;
    padding: 10px 0;
}

nav ul {
    display: flex;
    justify-content: center;
    list-style: none;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
}

nav ul li a:hover {
    text-decoration: underline;
}

section {
    padding: 20px 0;
    margin-bottom: 20px;
    background: #fff;
    border-radius: 5px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

section h2 {
    text-align: center;
    margin-bottom: 10px;
    font-size: 2rem;
}

#about img {
    display: block;
    max-width: 150px;
    margin: 10px auto;
    border-radius: 50%;
    border: 2px solid #333;
}

#skills ul {
    list-style: none;
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
}

#skills ul li {
    margin: 5px 10px;
    padding: 10px;
    background: #f4f4f9;
    border: 1px solid #ddd;
    border-radius: 5px;
}

#projects .project {
    margin: 20px 0;
    padding: 15px;
    border: 1px solid #ddd;
    border-radius: 5px;
    background: #f9f9f9;
}

#projects .project img {
    max-width: 100%;
    border-radius: 5px;
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    margin-top: 20px;
}

footer p {
    font-size: 0.9rem;
} 

/* Responsive Design */
@media (max-width: 768px) {
    nav ul {
        flex-direction: column;
    }

    #skills ul {
        flex-direction: column;
        align-items: center;
    }
} 
