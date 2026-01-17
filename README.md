<h1 align="center">Hey there 👋 I'm Juan Guerrero</h1>
<p align="center">
  <i>Backend Developer • Laravel Enthusiast • Software Engineer</i>  
</p>

<p align="center">
  <a href="https://juanguerrero.xyz">🌐 My Website</a> •
  <a href="mailto:contacto@juanguerrero.xyz">📧 Email</a> •
  <a href="https://github.com/JuanGuerreroDev">💻 GitHub</a>
</p>

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=JuanGuerreroDev&label=Profile%20views&color=blue&style=flat" alt="profile views"/>
</p>

---

### 📛 Tech Badges

<p align="center">
  <!-- Languages -->
  <img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=java&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-003B57?style=flat-square&logo=postgresql&logoColor=white" />

  <!-- Frameworks -->
  <img src="https://img.shields.io/badge/Laravel-F9322C?style=flat-square&logo=laravel&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" />

  <!-- Tools -->
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white" />
  <img src="https://img.shields.io/badge/WSL2-008080?style=flat-square&logo=windows&logoColor=white" />
</p>

---


### 🧠 About Me

Hi there! I'm Juan Guerrero, a passionate backend developer from Colombia 🇨🇴.  
I specialize in building robust, scalable, and elegant APIs using modern tools and clean architecture.  
I love solving complex backend problems and improving performance in real-world applications.

When I'm not coding, I'm either training my body, studying philosophy and spirituality, or solving a Rubik's cube faster than most people can blink. 🧊

---

### 🔧 Tech Stack

- **Languages:** PHP, Java, Python, SQL, HTML, CSS  
- **Frameworks:** Laravel, Spring Boot, Bootstrap, jQuery  
- **Databases:** PostgreSQL, MySQL  
- **Tools:** Git, Redis, Docker, GitHub Actions, WSL2, Nginx, REST APIs, Queues

---

### ✨ Recursive Profile (Just for Fun 💡)

```php
<?php

function buildProfile(array $skills, int $depth = 0): void
{
    $indent = str_repeat("  ", $depth);
    foreach ($skills as $key => $value) {
        if (is_array($value)) {
            echo "{$indent}$key:\n";
            buildProfile($value, $depth + 1);
        } else {
            echo "{$indent}- $value\n";
        }
    }
}

$profile = [
    'Name' => 'Juan Guerrero',
    'Roles' => ['Backend Developer', 'Engineer', 'SpeedCuber'],
    'Tech Stack' => [
        'Languages' => ['PHP', 'Java', 'Python', 'SQL'],
        'Frameworks' => ['Laravel', 'Spring Boot'],
        'Tools' => ['Git', 'Docker', 'Redis', 'WSL2']
    ]
];

buildProfile($profile);

```
