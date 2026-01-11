# Hi, I'm Sairam 👋
import { motion } from "framer-motion";

export default function Hero() {
  return (
    <section className="hero">
      <motion.h1
        initial={{ opacity: 0, y: 40 }}
        animate={{ opacity: 1, y: 0 }}
        transition={{ duration: 0.8 }}
      >
        Sai
      </motion.h1>

      <motion.p
        initial={{ opacity: 0 }}
        animate={{ opacity: 1 }}
        transition={{ delay: 0.6 }}
      >
        GIS Analyst · Spatial Data · Web Mapping
      </motion.p>
    </section>
  );
}

 MS Business Analytics @ Kent State University  
 Kent, Ohio, USA  

I work at the intersection of **Data Analytics, GIS, and Machine Learning**, with a strong focus on:
- Spatial analytics & road network extraction
- Computer vision using deep learning
- Business intelligence & data visualization

##  Technical Skills
- **Languages:** Python, SQL
- **Data & ML:** Pandas, NumPy, Scikit-learn, PyTorch
- **Deep Learning:** U-Net, DeepLabV3+, PSPNet, FPN
- **Visualization:** Power BI, Matplotlib, Seaborn
- **GIS:** ArcGIS, QGIS
- **Tools:** Jupyter Notebook, GitHub

##  Featured Projects
- **Road Network Extraction from Aerial Imagery**
  - Deep learning–based semantic segmentation using U-Net and DeepLabV3+
  - Evaluated IoU, F1-score, inference speed on high-resolution HDR imagery

- **Advanced Machine Learning Assignments**
  - Neural networks, CNNs, and applied deep learning experiments
  - Focus on model evaluation and architectural trade-offs

##  Connect with me
- LinkedIn: https://www.linkedin.com/in/jammusairam
