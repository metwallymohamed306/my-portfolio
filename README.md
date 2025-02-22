import React from "react";
import { FaLinkedin, FaEnvelope, FaPhone } from "react-icons/fa";

const App = () => {
  return (
    <div className="bg-white text-black font-sans p-6">
      {/* Header Section */}
      <header className="flex flex-col md:flex-row justify-between items-center border-b pb-4 mb-6">
        <h1 className="text-4xl font-bold">Mohamed Metwally</h1>
        <div className="flex items-center gap-4 mt-2 md:mt-0">
          <p className="text-lg font-semibold">Accountant | Financial Analyst | Data Analyst</p>
          <a href="tel:+201002347613" className="text-xl text-blue-600"><FaPhone /></a>
          <a href="mailto:your.email@example.com" className="text-xl text-blue-600"><FaEnvelope /></a>
          <a href="https://linkedin.com/in/yourprofile" className="text-xl text-blue-600"><FaLinkedin /></a>
        </div>
      </header>
      
      {/* About Section */}
      <section className="mb-6">
        <h2 className="text-2xl font-semibold border-b pb-2 mb-4">About Me</h2>
        <p>I am an ambitious finance and accounting professional with experience in financial analysis, banking operations, and data analytics. Passionate about leveraging technology in finance.</p>
      </section>

      {/* Education Section */}
      <section className="mb-6">
        <h2 className="text-2xl font-semibold border-b pb-2 mb-4">Education</h2>
        <p>Bachelor’s Degree in Accounting, Faculty of Commerce, Benha University (Expected Graduation: 2025) – GPA: Very Good</p>
      </section>

      {/* Certifications Section */}
      <section className="mb-6">
        <h2 className="text-2xl font-semibold border-b pb-2 mb-4">Certifications & Courses</h2>
        <ul className="list-disc ml-6">
          <li>Diploma in Accounting and Finance – Oxford Home Study College (2025)</li>
          <li>Diploma in Effective Bookkeeping and Payroll – Alison (2025)</li>
          <li>Master's in Business Administration (Mini MBA) – American Board of Professional Studies (2024)</li>
          <li>AI Career Essentials – ALX (2025)</li>
          <li>Financial Accounting Management and Reporting – UNICEF (2024)</li>
          <li>Liquidity Management – The Open University (2024)</li>
          <li>Data Literacy Certificate – SAS (2024)</li>
          <li>Certified International Trainer Diploma – Cambridge International Academy (2023)</li>
        </ul>
      </section>

      {/* Skills Section */}
      <section className="mb-6">
        <h2 className="text-2xl font-semibold border-b pb-2 mb-4">Skills</h2>
        <ul className="list-disc ml-6">
          <li>Financial Statement Analysis</li>
          <li>Banking Operations & Compliance</li>
          <li>Data Analysis using Python & SQL</li>
          <li>Advanced Excel & Financial Modeling</li>
          <li>Strong Communication & Negotiation Skills</li>
          <li>Proficiency in Arabic, English, and French</li>
        </ul>
      </section>

      {/* Experience Section */}
      <section className="mb-6">
        <h2 className="text-2xl font-semibold border-b pb-2 mb-4">Work Experience</h2>
        <ul className="list-disc ml-6">
          <li>Intern at CIB Bank (2024) – Gained experience in banking operations and financial services.</li>
          <li>Intern at Faisal Islamic Bank (2023) – Assisted in Islamic banking operations.</li>
          <li>Accountant at Business Compaq (2021-2023) – Managed financial records and assisted with audits.</li>
        </ul>
      </section>

      {/* Achievements Section */}
      <section className="mb-6">
        <h2 className="text-2xl font-semibold border-b pb-2 mb-4">Achievements & Activities</h2>
        <ul className="list-disc ml-6">
          <li>Ideal Student Award, Benha University (2024-2025)</li>
          <li>First Place in Scientific Research (2025)</li>
          <li>CMA Scholarship Recipient</li>
          <li>President, University Cities Students Union, Benha University</li>
          <li>Executive Director, Leaders Foundation</li>
          <li>Published Research Paper in International Economic Studies</li>
          <li>Technology Awareness Ambassador – Ministry of Social Solidarity</li>
          <li>Member, European Organization for Human Rights & Sustainable Development</li>
          <li>Volunteer at Life Makers Organization</li>
        </ul>
      </section>
    </div>
  );
};

export default App;
