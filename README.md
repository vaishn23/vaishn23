import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";

export default function Portfolio() {
  return (
    <main className="max-w-4xl mx-auto p-6 space-y-10">
      {/* Hero Section */}
      <section className="text-center">
        <h1 className="text-4xl font-bold mb-2">Hello, I'm Vaishnavi Ayyalasomayajula</h1>
        <p className="text-lg text-gray-700">Data Analyst</p>
      </section>

      {/* Brief Intro */}
      <section className="text-center">
        <p className="text-gray-700 max-w-xl mx-auto">
          Based in Austin, Texas, I am passionate about translating complex data into actionable insights. With a strong background in analytics and a commitment to continuous learning, I bring both technical and strategic value to organizations.
        </p>
      </section>

      {/* Skills with Icons (can be customized with logos later) */}
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

      {/* About Me */}
      <section>
        <h2 className="text-2xl font-semibold mb-4">About Me</h2>
        <p>
          I am a Master's student at Texas State University pursuing Data Analytics and Information Systems. My passion lies in solving real-world problems using data and building intelligent systems that support informed decision-making.
        </p>
      </section>

      {/* Resume Download */}
      <section>
        <h2 className="text-2xl font-semibold mb-4">Resume</h2>
        <a
          href="/Vaishnavi_Ayyalasomayajula_Resume.pdf"
          download
          className="inline-block"
        >
          <Button>Download My Resume</Button>
        </a>
      </section>

      {/* Experience */}
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

      {/* Education */}
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

      {/* Contact */}
      <section>
        <h2 className="text-2xl font-semibold mb-4">Contact Me</h2>
        <ul className="text-sm space-y-1">
          <li><strong>Email:</strong> vaishnavi.ayy@gmail.com</li>
          <li><strong>Phone:</strong> +1-214-892-7372</li>
          <li><strong>Location:</strong> Austin, TX, USA</li>
          <li><strong>LinkedIn:</strong> <a className="text-blue-600" href="https://www.linkedin.com/in/vaishnavi-ayyala/" target="_blank" rel="noopener noreferrer">vaishnavi-ayyala</a></li>
        </ul>
      </section>
    </main>
  );
}
