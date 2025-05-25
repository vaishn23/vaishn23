import React from "react";
import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";
import { Mail, Linkedin } from "lucide-react";

export default function Portfolio() {
  return (
    <main className="max-w-4xl mx-auto p-6 space-y-10">
      <section className="text-center space-y-2">
        <h1 className="text-4xl font-bold">Vaishnavi Ayyalasomayajula</h1>
        <p className="text-lg text-gray-600">Data Analyst | MS in Data Analytics and Information Systems</p>
        <div className="flex justify-center space-x-4 pt-2">
          <a href="mailto:vaishnavi.ayy@gmail.com" className="flex items-center space-x-1">
            <Mail className="w-4 h-4" /> <span>Email</span>
          </a>
          <a href="https://www.linkedin.com/in/vaishnavi-ayyala/" className="flex items-center space-x-1">
            <Linkedin className="w-4 h-4" /> <span>LinkedIn</span>
          </a>
        </div>
      </section>

      <section>
        <h2 className="text-2xl font-semibold mb-4">Summary</h2>
        <p>
          Data Analyst with hands-on experience in Python, SQL, Machine Learning, and data visualization. Skilled in data
          pipelines, statistical analysis, and delivering insights for research and sustainability projects.
        </p>
      </section>

      <section>
        <h2 className="text-2xl font-semibold mb-4">Education</h2>
        <Card>
          <CardContent className="p-4">
            <h3 className="text-xl font-bold">Texas State University</h3>
            <p>MS in Data Analytics and Information Systems, GPA: 3.5 (Jan 2024 – Dec 2025)</p>
            <p className="text-gray-600">Coursework: Machine Learning, Forecasting, Optimization, DBMS, Data Warehousing</p>
          </CardContent>
        </Card>
        <Card className="mt-4">
          <CardContent className="p-4">
            <h3 className="text-xl font-bold">BVRIT Hyderabad</h3>
            <p>B.Tech in Electronics and Communication Engineering (Jul 2023)</p>
          </CardContent>
        </Card>
      </section>

      <section>
        <h2 className="text-2xl font-semibold mb-4">Experience</h2>
        <Card>
          <CardContent className="p-4">
            <h3 className="font-bold">Graduate Assistant – Data Analyst</h3>
            <p className="text-gray-600">Department of Management, TXST (Aug 2024 – Present)</p>
            <ul className="list-disc ml-5 mt-2 space-y-1 text-sm">
              <li>Automated data pipelines using Python and SQL, improving efficiency by 40%.</li>
              <li>Integrated data from public sources and cleaned large datasets using Excel tools.</li>
              <li>Performed regression and clustering models to drive insights in sustainability research.</li>
              <li>Led interviews and site visits, co-authored research reports using ML + qualitative data.</li>
            </ul>
          </CardContent>
        </Card>
      </section>

      <section>
        <h2 className="text-2xl font-semibold mb-4">Projects</h2>
        <ul className="list-disc ml-5 space-y-1 text-sm">
          <li><strong>Supply Chain Carbon Tracker:</strong> Applied clustering to discover drivers of sustainability.</li>
          <li><strong>Stock Prediction:</strong> Used ARIMA and LSTM for forecasting tech company stock prices.</li>
          <li><strong>Real Estate Data Analysis:</strong> Built visual dashboards with Seaborn and Matplotlib.</li>
        </ul>
      </section>

      <section>
        <h2 className="text-2xl font-semibold mb-4">Skills</h2>
        <div className="grid grid-cols-2 gap-4 text-sm">
          <div>
            <p className="font-medium">Languages & Tools:</p>
            <p>Python, SQL, C, Excel, Tableau, Power BI, MAXQDA</p>
          </div>
          <div>
            <p className="font-medium">Frameworks:</p>
            <p>PySpark, TensorFlow, Pandas, Seaborn, Matplotlib, Airflow</p>
          </div>
          <div>
            <p className="font-medium">Platforms:</p>
            <p>AWS, GCP, Databricks, Hadoop, GitHub, Kaggle</p>
          </div>
          <div>
            <p className="font-medium">Certifications:</p>
            <p>Google Data Analytics, Tableau Certified</p>
          </div>
        </div>
      </section>

      <section>
        <h2 className="text-2xl font-semibold mb-4">Achievements</h2>
        <ul className="list-disc ml-5 text-sm">
          <li>Graduate Government Scholarship, Texas State University (2024-2025)</li>
          <li>Chair, IEEE GRSS at BVRIT Hyderabad (2021)</li>
          <li>SAA, Toastmasters International (2019–2020)</li>
        </ul>
      </section>
    </main>
  );
}
