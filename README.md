export default function ClinicalTrialDataProject() {
  return (
    <div className="p-6 space-y-4">
      <h1 className="text-2xl font-bold">Simulated Clinical Data Management Project</h1>

      <p className="text-base">This project simulates a data management workflow for a Phase II antimalarial clinical trial conducted in Malawi. It includes CRF design, MedDRA coding, query management, GCP documentation, and final reporting.</p>

      <ul className="list-disc list-inside">
        <li><strong>Protocol Summary:</strong> <code>protocol/protocol_summary.pdf</code></li>
        <li><strong>Case Report Form (CRF):</strong> <code>crfs/annotated_crf.pdf</code></li>
        <li><strong>EDC Mockup:</strong> <code>edc/redcap_mockup.xlsx</code></li>
        <li><strong>MedDRA Coding:</strong> <code>meddra/ae_mappings.xlsx</code></li>
        <li><strong>GCP SOPs:</strong> <code>gcp/sops.pdf</code></li>
        <li><strong>Query Log:</strong> <code>queries/query_log.xlsx</code></li>
        <li><strong>Final Dataset & Report:</strong> <code>outputs/cleaned_dataset.csv</code>, <code>outputs/final_report.pdf</code></li>
      </ul>

      <p className="text-base">Repository Structure:</p>
      <pre className="bg-gray-100 p-2 rounded">
{`clinical-data-sim-project/
├── protocol/
│   └── protocol_summary.pdf
├── crfs/
│   └── annotated_crf.pdf
├── edc/
│   └── redcap_mockup.xlsx
├── meddra/
│   └── ae_mappings.xlsx
├── gcp/
│   └── sops.pdf
├── queries/
│   └── query_log.xlsx
├── outputs/
│   ├── cleaned_dataset.csv
│   └── final_report.pdf
└── README.md`}
      </pre>

      <p className="text-base">To get started, clone this repository and replace placeholders with your simulated data and documents. Use the README to provide a walkthrough of your approach, assumptions, and tools used.</p>
    </div>
  );
}

