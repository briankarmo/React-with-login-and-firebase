import React, { useState } from 'react';
import {
  BrowserRouter as Router,
  Switch,
  Route,
  Link
} from 'react-router-dom';

function App() {
  const [loggedIn, setLoggedIn] = useState(false);

  const handleLogin = () => {
    setLoggedIn(true);
  }

  const handleLogout = () => {
    setLoggedIn(false);
  }

  return (
    <Router>
      <div>
        <nav>
          <ul>
            <li>
              <Link to="/">Home</Link>
            </li>
            <li>
              <Link to="/about">About</Link>
            </li>
            <li>
              <Link to="/contact">Contact</Link>
            </li>
            {loggedIn ? (
              <li>
                <button onClick={handleLogout}>Logout</button>
              </li>
            ) : (
              <li>
                <Link to="/login">Login</Link>
              </li>
            )}
          </ul>
        </nav>

        <Switch>
          <Route path="/about">
            <About />
          </Route>
          <Route path="/contact">
            <Contact />
          </Route>
          {loggedIn ? (
            <Route path="/dashboard">
              <Dashboard />
            </Route>
          ) : (
            <Route path="/login">
              <Login onLogin={handleLogin} />
            </Route>
          )}
          <Route path="/">
            <Home />
          </Route>
        </Switch>
      </div>
    </Router>
  );
}

function Home() {
  return (
    <div>
      <h2>Home</h2>
      <p>Welcome to my website!</p>
    </div>
  );
}

function About() {
  return (
    <div>
      <h2>About</h2>
      <p>Learn more about us.</p>
    </div>
  );
}

function Contact() {
  return (
    <div>
      <h2>Contact</h2>
      <p>Get in touch with us.</p>
    </div>
  );
}

function Dashboard() {
  return (
    <div>
      <h2>Dashboard</h2>
      <p>Welcome to your dashboard.</p>
    </div>
  );
}

function Login(props) {
  const [username, setUsername] = useState('');
  const [password, setPassword] = useState('');

  const handleSubmit = (event) => {
    event.preventDefault();
    props.onLogin();
  }

  return (
    <div>
      <h2>Login</h2>
      <form onSubmit={handleSubmit}>
        <div>
          <label>Username:</label>
          <input type="text" value={username} onChange={(event) => setUsername(event.target.value)} />
        </div>
        <div>
          <label>Password:</label>
          <input type="password" value={password} onChange={(event) => setPassword(event.target.value)} />
        </div>
        <button type="submit">Login</button>
      </form>
    </div>
  );
}

export default App;
