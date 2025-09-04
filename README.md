body {
  font-family: Arial, sans-serif;
  background: linear-gradient(to right, #74ebd5, #ACB6E5);
  margin: 0;
  padding: 20px;
  text-align: center;
}

.container {
  display: none;
  margin-top: 20px;
}

.images {
  display: flex;
  justify-content: center;
  gap: 20px;
  margin-top: 20px;
}

.images img {
  max-width: 45%;
  border-radius: 10px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
}

button, input[type="file"] {
  margin: 10px;
  padding: 10px 20px;
  border: none;
  border-radius: 8px;
  background-color: #4CAF50;
  color: white;
  font-size: 16px;
  cursor: pointer;
  transition: 0.3s;
}

button:hover, input[type="file"]:hover {
  background-color: #45a049;
}

.filter-options {
  display: none;
  flex-wrap: wrap;
  justify-content: center;
  gap: 10px;
  margin-top: 20px;
}

.filter-options button {
  background-color: #2196F3;
}

.filter-options button:hover {
  background-color: #0b7dda;
}
