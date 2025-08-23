from docx import Document

# Create a new Word document
doc = Document()

# Add heading
doc.add_heading("Cover Letter", level=1)

# Add content
cover_letter = f"""
Parijat Roy
Email: royparijat95@gmail.com | Phone: +91-81318-93039
LinkedIn: www.linkedin.com/in/parijat-roy-1907a5260 | GitHub: https://github.com/CYBORGBC

[Date]

Hiring Manager
Deloitte India – Technology & Transformation
EAD – Intelligent Automation & Agentic AI Analyst

Dear Hiring Manager,

I am writing to express my interest in the Analyst position at Deloitte India within the Technology & Transformation – EAD – Intelligent Automation & Agentic AI team. As a B.Tech. Computer Science & Systems Engineering student at Kalinga Institute of Industrial Technology with hands-on experience in Artificial Intelligence, Machine Learning, and Data Science projects, I am excited about the opportunity to contribute to Deloitte’s innovation-driven initiatives.

My academic and project experiences have equipped me with a solid foundation in developing intelligent systems. For instance, I built an **Invoice Payment Delay Predictor & Cash-Flow Risk Dashboard**, which leveraged machine learning to provide actionable business insights. Additionally, I developed a **Bankruptcy Predictor** using XGBoost, Decision Trees, and Logistic Regression to analyze financial data and forecast risks. Furthermore, my work on **Secret Image Sharing using GANs** demonstrated my ability to integrate computer vision with cryptographic principles, ensuring data confidentiality and secure communication.

I am proficient in Python, TensorFlow, PyTorch, and Scikit-learn, with strong problem-solving skills in predictive modeling, natural language processing, and intelligent automation. I also have experience with tools such as Hugging Face Transformers and LangChain, which aligns well with Deloitte’s focus on next-generation AI applications, including agentic AI.

What excites me most about Deloitte is the chance to work at the forefront of technology consulting, developing AI-driven automation solutions that deliver tangible business transformation. I am confident that my technical expertise, combined with my passion for innovation, make me a strong candidate for this Analyst role.

I would welcome the opportunity to further discuss how my background, skills, and enthusiasm align with the goals of Deloitte India. Thank you for considering my application. I look forward to the possibility of contributing to your esteemed team.

Sincerely,  
Parijat Roy
"""

doc.add_paragraph(cover_letter)

# Save the document
output_path = "/mnt/data/Parijat_Roy_Deloitte_Cover_Letter.docx"
doc.save(output_path)

output_path
