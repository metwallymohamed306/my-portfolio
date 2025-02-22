import React from "react";
import { FaLinkedin, FaEnvelope, FaPhone } from "react-icons/fa";

const App = () => {
  return (
    <div className="bg-gray-50 dark:bg-gray-900 text-gray-900 dark:text-white font-sans p-8 max-w-5xl mx-auto shadow-2xl rounded-2xl transition duration-300">
      <header className="text-center mb-10">
        <h1 className="text-5xl font-extrabold text-blue-600 dark:text-blue-400">Mohamed Metwally</h1>
        <p className="text-xl font-medium mt-3">Accountant | Financial Analyst | Data Analyst</p>
        <div className="flex justify-center gap-6 mt-4 text-blue-600 dark:text-blue-400">
          <a href="tel:+201002347613" className="text-2xl hover:text-blue-800 dark:hover:text-blue-300 transition"><FaPhone /></a>
          <a href="mailto:MohamedMetwally.Mohamed@outlook.com" className="text-2xl hover:text-blue-800 dark:hover:text-blue-300 transition"><FaEnvelope /></a>
          <a href="https://www.linkedin.com/in/mohamed-metwally-0182bb2b5" className="text-2xl hover:text-blue-800 dark:hover:text-blue-300 transition"><FaLinkedin /></a>
        </div>
      </header>

      <section className="space-y-6">
        <div className="bg-white dark:bg-gray-800 p-6 rounded-lg shadow-md">
          <h2 className="text-2xl font-semibold text-blue-600 dark:text-blue-400 border-b pb-2 mb-4">Objective</h2>
          <p className="text-gray-700 dark:text-gray-300">Seeking a Banker position to apply my skills in financial management, customer service, and banking operations. Passionate about enhancing client experience and optimizing financial processes through data analysis and digital banking solutions.</p>
        </div>

        <div className="bg-white dark:bg-gray-800 p-6 rounded-lg shadow-md">
          <h2 className="text-2xl font-semibold text-blue-600 dark:text-blue-400 border-b pb-2 mb-4">Education</h2>
          <p className="text-gray-700 dark:text-gray-300">Bachelor’s Degree in Accounting, Faculty of Commerce, Benha University (Expected Graduation: 2025) – GPA: Very Good</p>
        </div>

        <div className="bg-white dark:bg-gray-800 p-6 rounded-lg shadow-md">
          <h2 className="text-2xl font-semibold text-blue-600 dark:text-blue-400 border-b pb-2 mb-4">Certifications & Courses</h2>
          <ul className="list-disc ml-6 text-gray-700 dark:text-gray-300 grid grid-cols-1 md:grid-cols-2 gap-3">
            <li>Diploma in Accounting and Finance – Oxford Home Study College (2025)</li>
            <li>Mini MBA – American Board of Professional Studies (2024)</li>
            <li>AI Career Essentials – ALX (2025)</li>
            <li>AWS Cloud Economics for Startups – Amazon Web Services (AWS) (2025)</li>
            <li>Financial Services – AWS (2024)</li>
            <li>Liquidity Management – The Open University (2024)</li>
            <li>Data Literacy Certificate – SAS (2024)</li>
            <li>Financial Accounting Management and Reporting – UNICEF (2024)</li>
          </ul>
        </div>

        <div className="bg-white dark:bg-gray-800 p-6 rounded-lg shadow-md">
          <h2 className="text-2xl font-semibold text-blue-600 dark:text-blue-400 border-b pb-2 mb-4">Achievements & Activities</h2>
          <ul className="list-disc ml-6 text-gray-700 dark:text-gray-300 grid grid-cols-1 md:grid-cols-2 gap-3">
            <li>Ideal Student Award – Benha University (2024-2025)</li>
            <li>First Place in Scientific Research (2025)</li>
            <li>CMA Scholarship Recipient</li>
            <li>President, University Cities Students Union, Benha University</li>
            <li>Executive Director, Leaders Foundation</li>
            <li>Published Research Paper in International Economic Studies</li>
            <li>Technology Awareness Ambassador – Ministry of Social Solidarity</li>
            <li>Member, European Organization for Human Rights & Sustainable Development</li>
            <li>Volunteer at Life Makers Organization</li>
          </ul>
        </div>
      </section>
    </div>
  );
};

export default App;
