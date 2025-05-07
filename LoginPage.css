import React, { useState } from "react";
import "./LoginPage.css";

export default function LoginPage() {
  const [username, setUsername] = useState("");
  const [password, setPassword] = useState("");
  const [confirmPassword, setConfirmPassword] = useState("");
  const [email, setEmail] = useState("");

  const handleSubmit = (e) => {
    e.preventDefault();
    if (password !== confirmPassword) {
      alert("As senhas não coincidem!");
      return;
    }
    alert("Conta criada com sucesso!");
  };

  return (
    <div className="login-container">
      <div className="overlay"></div>
      <div className="form-container">
        <div className="profile-icon">
          <i className="fas fa-user-circle"></i>
        </div>
        <h2>Criar</h2>
        <form onSubmit={handleSubmit}>
          <label>
            Usuário
            <input
              type="text"
              value={username}
              placeholder="Digite seu nome de usuário"
              onChange={(e) => setUsername(e.target.value)}
              required
            />
          </label>
          <label>
            Senha
            <input
              type="password"
              value={password}
              placeholder="Digite sua senha"
              onChange={(e) => setPassword(e.target.value)}
              required
            />
          </label>
          <label>
            Confirmação da senha
            <input
              type="password"
              value={confirmPassword}
              placeholder="Confirme sua senha"
              onChange={(e) => setConfirmPassword(e.target.value)}
              required
            />
          </label>
          <label>
            E-mail
            <input
              type="email"
              value={email}
              placeholder="Digite seu e-mail"
              onChange={(e) => setEmail(e.target.value)}
              required
            />
          </label>
          <div className="buttons">
            <button type="submit" className="btn-save">Salvar</button>
            <button type="button" className="btn-cancel" onClick={() => alert("Cancelado!")}>
              Cancelar
            </button>
          </div>
        </form>
      </div>
    </div>
  );
}
