document.addEventListener('DOMContentLoaded', function() {
    // Dados do currículo
    const data = {
        name: "Seu Nome",
        profession: "Sua Profissão",
        email: "seu-email@example.com",
        phone: "1234-5678",
        linkedin: "https://linkedin.com/in/seu-perfil",
        summary: "Seu resumo profissional aqui.",
        experience: [
            { title: "Cargo", company: "Nome da Empresa", date: "Data de início - Data de término", description: "Descrição das responsabilidades e conquistas" }
            // Adicione mais experiências aqui
        ],
        education: [
            { degree: "Grau Acadêmico", institution: "Nome da Instituição", year: "Ano de Conclusão", description: "Descrição do curso, se desejado" }
            // Adicione mais formações aqui
        ],
        skills: [
            "Habilidade 1",
            "Habilidade 2"
            // Adicione mais habilidades aqui
        ]
    };

    // Preencher informações no HTML
    document.getElementById('name').textContent = data.name;
    document.getElementById('profession').textContent = data.profession;
    document.getElementById('email').href = `mailto:${data.email}`;
    document.getElementById('email').textContent = data.email;
    document.getElementById('phone').textContent = data.phone;
    document.getElementById('linkedin').href = data.linkedin;
    document.getElementById('linkedin').textContent = data.linkedin;
    document.getElementById('summary').textContent = data.summary;

    // Preencher experiência
    const experienceList = document.getElementById('experience-list');
    data.experience.forEach(exp => {
        const li = document.createElement('li');
        li.innerHTML = `<h3>${exp.title} - ${exp.company}</h3><p>${exp.date}</p><p>${exp.description}</p>`;
        experienceList.appendChild(li);
    });

    // Preencher educação
    const educationList = document.getElementById('education-list');
    data.education.forEach(edu => {
        const li = document.createElement('li');
        li.innerHTML = `<h3>${edu.degree} - ${edu.institution}</h3><p>${edu.year}</p><p>${edu.description}</p>`;
        educationList.appendChild(li);
    });

    // Preencher habilidades
    const skillsList = document.getElementById('skills-list');
    data.skills.forEach(skill => {
        const li = document.createElement('li');
        li.textContent = skill;
        skillsList.appendChild(li);
    });

    // Preencher nome do rodapé
    document.getElementById('footer-name').textContent = data.name;
});
