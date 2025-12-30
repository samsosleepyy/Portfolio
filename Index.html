import React, { useState, useEffect } from 'react';
import { Code, Users, Video, Server, GraduationCap, Mail, ExternalLink, Menu, X, BookOpen, Terminal, Globe, Cpu, Zap, Target, Award, ShoppingBag, Brain } from 'lucide-react';
import { motion, useScroll, AnimatePresence } from 'framer-motion';

// --- Animation Variants ---
const fadeIn = {
  initial: { opacity: 0 },
  animate: { opacity: 1 },
  transition: { duration: 0.6 }
};

const fadeInUp = {
  initial: { opacity: 0, y: 20 },
  animate: { opacity: 1, y: 0 },
  transition: { duration: 0.6, ease: [0.22, 1, 0.36, 1] }
};

const staggerContainer = {
  initial: {},
  animate: {
    transition: {
      staggerChildren: 0.1,
    },
  },
};

const slideInLeft = {
  initial: { opacity: 0, x: -50 },
  animate: { opacity: 1, x: 0 },
  transition: { duration: 0.6, ease: [0.22, 1, 0.36, 1] }
};

const slideInRight = {
  initial: { opacity: 0, x: 50 },
  animate: { opacity: 1, x: 0 },
  transition: { duration: 0.6, ease: [0.22, 1, 0.36, 1] }
};

const Portfolio = () => {
  const [isMenuOpen, setIsMenuOpen] = useState(false);
  const [activeSection, setActiveSection] = useState('home');
  const { scrollY } = useScroll();

  // Scroll Spy Logic
  useEffect(() => {
    const handleScroll = () => {
      const sections = ['home', 'about', 'passion', 'projects', 'contact'];
      const scrollPosition = window.scrollY + 100;

      for (const section of sections) {
        const element = document.getElementById(section);
        if (element && element.offsetTop <= scrollPosition && (element.offsetTop + element.offsetHeight) > scrollPosition) {
          setActiveSection(section);
        }
      }
    };

    window.addEventListener('scroll', handleScroll);
    return () => window.removeEventListener('scroll', handleScroll);
  }, []);

  const scrollTo = (id) => {
    const element = document.getElementById(id);
    if (element) {
      element.scrollIntoView({ behavior: 'smooth' });
      setIsMenuOpen(false);
    }
  };

  return (
    <div className="min-h-screen bg-slate-950 text-cyan-50 font-sans selection:bg-cyan-500 selection:text-black overflow-x-hidden relative">
      
      {/* Background Grid Effect */}
      <div className="fixed inset-0 z-0 opacity-10 pointer-events-none" 
           style={{ 
             backgroundImage: 'linear-gradient(rgba(6, 182, 212, 0.1) 1px, transparent 1px), linear-gradient(90deg, rgba(6, 182, 212, 0.1) 1px, transparent 1px)', 
             backgroundSize: '40px 40px' 
           }}>
      </div>
      
      {/* Navigation */}
      <motion.nav
        initial={{ y: -100 }}
        animate={{ y: 0 }}
        transition={{ duration: 0.5 }}
        className="fixed top-0 w-full bg-slate-950/90 backdrop-blur-md border-b border-cyan-900/30 z-50 shadow-lg shadow-cyan-900/10"
      >
        <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
          <div className="flex justify-between items-center h-20">
            <motion.div 
              whileHover={{ scale: 1.05 }}
              className="flex-shrink-0 flex items-center cursor-pointer group" 
              onClick={() => scrollTo('home')}
            >
              <Cpu className="text-cyan-400 mr-2 group-hover:animate-pulse" />
              <span className="font-bold text-2xl tracking-tighter text-white">THANAKRIT<span className="text-cyan-400">.DEV</span></span>
            </motion.div>
            
            {/* Desktop Menu */}
            <div className="hidden md:flex space-x-2">
              {['Home', 'About', 'Passion', 'Projects', 'Contact'].map((item) => (
                <motion.button
                  key={item}
                  whileHover={{ scale: 1.05, textShadow: "0 0 8px rgba(6,182,212,0.8)" }}
                  whileTap={{ scale: 0.95 }}
                  onClick={() => scrollTo(item.toLowerCase())}
                  className={`px-4 py-2 rounded font-medium text-sm transition-all duration-200 relative overflow-hidden group ${
                    activeSection === item.toLowerCase() 
                      ? 'text-cyan-400 bg-cyan-950/50 border border-cyan-500/50 shadow-[0_0_15px_rgba(6,182,212,0.4)]' 
                      : 'text-slate-400 hover:text-cyan-300 hover:bg-cyan-950/20'
                  }`}
                >
                  <span className="relative z-10">{item}</span>
                  {activeSection === item.toLowerCase() && (
                    <motion.div 
                      layoutId="activeTab"
                      className="absolute inset-0 bg-cyan-500/10"
                      initial={false}
                      transition={{ type: "spring", stiffness: 500, damping: 30 }}
                    />
                  )}
                </motion.button>
              ))}
            </div>

            {/* Mobile Menu Button */}
            <div className="md:hidden flex items-center">
              <button onClick={() => setIsMenuOpen(!isMenuOpen)} className="text-cyan-400 hover:text-white transition">
                {isMenuOpen ? <X size={28} /> : <Menu size={28} />}
              </button>
            </div>
          </div>
        </div>

        {/* Mobile Menu Dropdown */}
        <AnimatePresence>
          {isMenuOpen && (
            <motion.div
              initial={{ opacity: 0, height: 0 }}
              animate={{ opacity: 1, height: 'auto' }}
              exit={{ opacity: 0, height: 0 }}
              className="md:hidden bg-slate-900 border-b border-cyan-900/50 overflow-hidden"
            >
              <div className="px-2 pt-2 pb-4 space-y-1">
                {['Home', 'About', 'Passion', 'Projects', 'Contact'].map((item) => (
                  <button
                    key={item}
                    onClick={() => scrollTo(item.toLowerCase())}
                    className="block w-full text-left px-4 py-3 rounded-md text-base font-medium text-slate-300 hover:text-cyan-400 hover:bg-cyan-950/30 border-l-2 border-transparent hover:border-cyan-500 transition-all"
                  >
                    {item}
                  </button>
                ))}
              </div>
            </motion.div>
          )}
        </AnimatePresence>
      </motion.nav>

      {/* Hero Section */}
      <section id="home" className="relative pt-32 pb-20 md:pt-48 md:pb-32 px-4 overflow-hidden min-h-screen flex items-center">
        {/* Background Gradients */}
        <div className="absolute top-0 right-0 w-[500px] h-[500px] bg-blue-600/20 rounded-full blur-[120px] mix-blend-screen pointer-events-none" />
        <div className="absolute bottom-0 left-0 w-[500px] h-[500px] bg-cyan-600/10 rounded-full blur-[120px] mix-blend-screen pointer-events-none" />

        <div className="max-w-7xl mx-auto w-full grid md:grid-cols-2 gap-12 items-center relative z-10">
          <motion.div 
            variants={staggerContainer}
            initial="initial"
            animate="animate"
            className="text-center md:text-left space-y-8"
          >
            <motion.div variants={fadeInUp} className="inline-flex items-center gap-2 px-4 py-2 bg-cyan-950/50 border border-cyan-500/30 text-cyan-400 rounded-lg text-sm font-semibold tracking-wide shadow-[0_0_10px_rgba(6,182,212,0.2)]">
              <span className="w-2 h-2 bg-cyan-400 rounded-full animate-pulse"></span>
              Aspiring Educational Technologist
            </motion.div>
            
            <motion.h1 variants={fadeInUp} className="text-5xl md:text-7xl font-bold text-white leading-tight tracking-tight">
              Hello, I am <br />
              <span className="relative inline-block mt-2">
                <span className="absolute -inset-1 bg-gradient-to-r from-cyan-500 to-blue-600 blur opacity-30 animate-pulse"></span>
                <span className="relative text-transparent bg-clip-text bg-gradient-to-r from-cyan-400 via-blue-400 to-purple-400 drop-shadow-sm">
                  Thanakrit Bupphataku
                </span>
              </span>
            </motion.h1>
            
            <motion.p variants={fadeInUp} className="text-lg md:text-xl text-slate-300 leading-relaxed max-w-lg mx-auto md:mx-0 border-l-4 border-cyan-500/50 pl-6">
              "เปลี่ยนภาษาคน ให้เป็นภาษาโค้ด เปลี่ยนเรื่องซับซ้อน ให้เป็นเรื่องเข้าใจง่าย"
              <br/><br/>
              นักเรียนศิลป์-ภาษาที่หลงใหลในโลกของเทคโนโลยี มุ่งมั่นที่จะผสานทักษะการสื่อสารและการเขียนโปรแกรม เพื่อพัฒนานวัตกรรมทางการศึกษาในอนาคต
            </motion.p>
            
            <motion.div variants={fadeInUp} className="flex flex-col sm:flex-row gap-6 justify-center md:justify-start pt-6">
              <motion.button 
                whileHover={{ scale: 1.05, boxShadow: "0 0 25px rgba(6,182,212,0.6)" }}
                whileTap={{ scale: 0.95 }}
                onClick={() => scrollTo('projects')} 
                className="px-8 py-4 bg-cyan-600 text-white text-lg font-bold rounded-lg shadow-[0_0_15px_rgba(6,182,212,0.4)] hover:bg-cyan-500 transition-all relative overflow-hidden group"
              >
                <div className="absolute inset-0 bg-white/20 translate-y-full group-hover:translate-y-0 transition-transform duration-300" />
                <span className="relative z-10">View My Work</span>
              </motion.button>
              
              <motion.button 
                whileHover={{ scale: 1.05, boxShadow: "0 0 20px rgba(168,85,247,0.4)", borderColor: "#a855f7" }}
                whileTap={{ scale: 0.95 }}
                onClick={() => scrollTo('contact')} 
                className="px-8 py-4 bg-transparent text-cyan-400 hover:text-purple-400 text-lg font-bold rounded-lg border border-cyan-500/50 hover:bg-slate-900 transition-all"
              >
                Contact Me
              </motion.button>
            </motion.div>
          </motion.div>
          
          <motion.div 
            initial={{ opacity: 0, x: 50 }}
            animate={{ opacity: 1, x: 0 }}
            transition={{ duration: 0.8, delay: 0.2 }}
            className="flex justify-center relative items-center"
          >
            {/* System Background Container */}
            <div className="relative w-72 h-72 md:w-96 md:h-96 flex items-center justify-center">
              
              {/* Spinning Outer Ring (The System) */}
              <motion.div 
                animate={{ rotate: 360 }}
                transition={{ duration: 20, repeat: Infinity, ease: "linear" }}
                className="absolute inset-0 border-2 border-dashed border-cyan-500/30 rounded-full z-0"
              ></motion.div>
              
              {/* Rotating Squares (Behind) */}
              <motion.div 
                animate={{ rotate: 360 }}
                transition={{ duration: 15, repeat: Infinity, ease: "linear" }}
                className="absolute inset-4 border border-cyan-500/20 rounded-3xl z-0"
              ></motion.div>
              <motion.div 
                animate={{ rotate: -360 }}
                transition={{ duration: 15, repeat: Infinity, ease: "linear" }}
                className="absolute inset-4 border border-purple-500/20 rounded-3xl transform scale-105 z-0"
              ></motion.div>

              {/* Central Tech Panel (Static Background for Image) */}
              <div className="absolute inset-8 bg-slate-900/80 backdrop-blur-sm border border-cyan-500/30 rounded-xl z-0 shadow-[0_0_30px_rgba(6,182,212,0.1)]"></div>

              {/* The Image (Popped Out / Outside) */}
              <motion.div 
                initial={{ y: 20, opacity: 0 }}
                animate={{ y: 0, opacity: 1 }}
                transition={{ duration: 0.8, delay: 0.4 }}
                whileHover={{ scale: 1.05, y: -5 }}
                className="relative z-20 w-[110%] h-[110%] -mt-8 flex items-end justify-center pointer-events-auto"
              >
                 <img 
                  src="assist/profile.png" 
                  alt="Thanakrit Profile" 
                  className="w-full h-full object-contain drop-shadow-[0_0_20px_rgba(6,182,212,0.5)] filter contrast-110"
                />
              </motion.div>
              
              {/* Floating Stat Boxes (Foreground) */}
              <motion.div 
                initial={{ x: -50, opacity: 0 }}
                animate={{ x: 0, opacity: 1 }}
                transition={{ delay: 0.8 }}
                whileHover={{ scale: 1.1, rotate: -2 }}
                className="absolute -bottom-2 -left-8 bg-slate-900/90 border border-cyan-500/50 p-4 rounded-lg shadow-[0_0_15px_rgba(6,182,212,0.3)] z-30 backdrop-blur-md"
              >
                <div className="flex items-center gap-3">
                  <Terminal className="text-cyan-400" />
                  <div>
                    <p className="text-xs text-cyan-500 font-semibold">Coding Since</p>
                    <p className="font-bold text-white">Middle School</p>
                  </div>
                </div>
              </motion.div>

              <motion.div 
                initial={{ x: 50, opacity: 0 }}
                animate={{ x: 0, opacity: 1 }}
                transition={{ delay: 1.0 }}
                whileHover={{ scale: 1.1, rotate: 2 }}
                className="absolute -top-2 -right-8 bg-slate-900/90 border border-purple-500/50 p-4 rounded-lg shadow-[0_0_15px_rgba(168,85,247,0.3)] z-30 backdrop-blur-md"
              >
                 <div className="flex items-center gap-3">
                  <Users className="text-purple-400" />
                  <div>
                    <p className="text-xs text-purple-500 font-semibold">Community</p>
                    <p className="font-bold text-white">3,000+ Members</p>
                  </div>
                </div>
              </motion.div>
            </div>
          </motion.div>
        </div>
      </section>

      {/* About Section */}
      <section id="about" className="py-20 bg-slate-900 border-y border-cyan-900/30 relative">
        <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
          <motion.div 
            variants={fadeInUp}
            initial="initial"
            whileInView="animate"
            viewport={{ once: true }}
            className="mb-16 flex items-center gap-4"
          >
            <div className="h-1 w-12 bg-cyan-500 rounded-full shadow-[0_0_10px_rgba(6,182,212,0.8)]"></div>
            <h2 className="text-3xl md:text-4xl font-bold text-white">About Me</h2>
          </motion.div>
          
          <div className="grid md:grid-cols-2 gap-12">
             <motion.div 
               variants={slideInLeft}
               initial="initial"
               whileInView="animate"
               viewport={{ once: true }}
               whileHover={{ scale: 1.02 }}
               className="bg-slate-950/50 p-8 rounded-xl border border-cyan-500/20 shadow-lg h-full hover:border-cyan-500/40 hover:shadow-[0_0_20px_rgba(6,182,212,0.15)] transition-all duration-300"
             >
                <div className="space-y-8">
                  <div className="flex items-start gap-4">
                    <div className="bg-cyan-900/20 p-3 rounded-lg text-cyan-400 border border-cyan-500/30">
                      <GraduationCap size={24} />
                    </div>
                    <div>
                      <h3 className="font-bold text-xl text-white">Education</h3>
                      <p className="text-slate-300 mt-1 font-medium">โรงเรียนปักธงชัยประชานิรมิต</p>
                      <p className="text-slate-400 text-sm mt-1">ระดับชั้นมัธยมศึกษาปีที่ 6</p>
                      <p className="text-slate-400 text-sm">แผนการเรียน: ศิลป์-ภาษาญี่ปุ่น</p>
                    </div>
                  </div>
                  
                  <div className="flex items-start gap-4">
                    <div className="bg-purple-900/20 p-3 rounded-lg text-purple-400 border border-purple-500/30">
                      <Target size={24} />
                    </div>
                    <div>
                      <h3 className="font-bold text-xl text-white">Future Goal</h3>
                      <p className="text-slate-300 mt-1">คณะครุศาสตร์ / ศึกษาศาสตร์</p>
                      <p className="text-purple-400 font-semibold">สาขาเทคโนโลยีการศึกษา</p>
                    </div>
                  </div>

                   <div className="flex items-start gap-4">
                    <div className="bg-blue-900/20 p-3 rounded-lg text-blue-400 border border-blue-500/30">
                      <Code size={24} />
                    </div>
                    <div>
                      <h3 className="font-bold text-xl text-white">Technical Skills</h3>
                      <div className="flex flex-wrap gap-2 mt-3">
                        {['Lua Scripting', 'Web Development', 'Community Management', 'Content Creation'].map((skill) => (
                          <motion.span 
                            key={skill}
                            whileHover={{ scale: 1.1, backgroundColor: "rgba(30, 41, 59, 1)", borderColor: "rgba(6, 182, 212, 0.8)" }}
                            className="px-3 py-1 bg-slate-800 border border-slate-700 rounded-full text-xs text-cyan-300 font-medium cursor-default transition-all"
                          >
                            {skill}
                          </motion.span>
                        ))}
                      </div>
                    </div>
                  </div>
                </div>
             </motion.div>
             
             <motion.div
                variants={slideInRight}
                initial="initial"
                whileInView="animate"
                viewport={{ once: true }}
                className="flex flex-col justify-center"
             >
                <div className="mb-6">
                  <h3 className="text-2xl font-bold text-white mb-3">Passion & Determination</h3>
                  <p className="text-cyan-500 font-medium tracking-wide text-sm mb-4">ความมุ่งมั่นสู่รั้วราชภัฏนครราชสีมา</p>
                </div>
                
                <div className="space-y-6 text-slate-300 leading-relaxed text-lg">
                  <p>
                    ผมมีความตั้งใจอย่างแรงกล้าที่จะเข้าศึกษาต่อที่ <span className="text-cyan-400 font-bold">มหาวิทยาลัยราชภัฏนครราชสีมา</span> เส้นทางของผมไม่ได้เริ่มต้นด้วยความพร้อม ผมเริ่มหัดเขียนโค้ด <b>Lua</b> ตั้งแต่ ม.ต้น โดยต้องอาศัย <b>ร้านอินเทอร์เน็ตคาเฟ่</b> ในการฝึกฝนเพราะที่บ้านไม่มีคอมพิวเตอร์ จนถึงปัจจุบันที่ผมพัฒนาเว็บไซต์ ผมก็ยังคงมุ่งมั่นเขียนโค้ดผ่าน <b>VS Code (Web Version)</b> บนอุปกรณ์ที่มีจำกัด
                  </p>
                  <p>
                    นี่คือบทพิสูจน์ถึงความพยายามและความทุ่มเทของผม ที่จะไม่ยอมให้อุปสรรคทางฐานะมาปิดกั้นการเรียนรู้ ผมสร้างผลงานทั้งหมดนี้ขึ้นมาด้วยตนเอง เพื่อแสดงให้เห็นว่าผมพร้อมแค่ไหนที่จะเข้าไปเติบโตในรั้วมหาวิทยาลัยแห่งนี้
                  </p>

                  <div className="grid sm:grid-cols-2 gap-4 mt-4">
                    <motion.div 
                      whileHover={{ y: -5, borderColor: "rgba(6, 182, 212, 0.6)" }}
                      className="bg-slate-900/50 p-4 rounded-lg border border-cyan-500/30 transition-all duration-300"
                    >
                      <h4 className="text-cyan-400 font-bold mb-2 flex items-center gap-2">
                        <Code size={18} /> สิ่งที่ถนัด
                      </h4>
                      <p className="text-sm text-slate-400 leading-relaxed">
                        ผมมีความเชี่ยวชาญในภาษา <b>HTML, CSS</b> สำหรับการทำ Web Design และภาษา <b>Lua</b> สำหรับการเขียนระบบเกมใน Roblox ซึ่งเป็นทักษะที่ผมฝึกฝนจนชำนาญ
                      </p>
                    </motion.div>

                    <motion.div 
                      whileHover={{ y: -5, borderColor: "rgba(236, 72, 153, 0.6)" }}
                      className="bg-slate-900/50 p-4 rounded-lg border border-pink-500/30 transition-all duration-300"
                    >
                      <h4 className="text-pink-400 font-bold mb-2 flex items-center gap-2">
                        <Brain size={18} /> การแก้ปัญหา
                      </h4>
                      <p className="text-sm text-slate-400 leading-relaxed">
                        ผมเรียนรู้สิ่งที่ไม่สนใจได้ช้า แต่ผมแก้ไขด้วยการ <b>"เชื่อมโยงกับสิ่งที่ชอบ"</b> เช่น นำทฤษฎีที่น่าเบื่อมาแปลงเป็นลอจิกในการเขียนโค้ด ทำให้ผมเข้าใจและสนุกกับมันได้
                      </p>
                    </motion.div>
                  </div>

                  <p className="text-base text-slate-400 border-l-2 border-slate-700 pl-4 italic">
                    "เพราะผมเชื่อว่า การเป็นครูยุคใหม่ ไม่ใช่แค่การมีความรู้ แต่คือการรู้จักปรับตัวและประยุกต์ใช้สิ่งที่มี เพื่อแก้ไขปัญหาและพัฒนาการเรียนรู้ให้ดียิ่งขึ้น"
                  </p>
                </div>
             </motion.div>
          </div>
        </div>
      </section>

      {/* Passion & Journey Section */}
      <section id="passion" className="py-24 bg-black relative overflow-hidden">
        {/* Abstract Backgrounds */}
        <div className="absolute inset-0 bg-[radial-gradient(circle_at_center,_var(--tw-gradient-stops))] from-blue-900/20 via-slate-950 to-slate-950"></div>

        <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
          <motion.div 
            variants={fadeInUp}
            initial="initial"
            whileInView="animate"
            viewport={{ once: true }}
            className="text-center mb-16"
          >
            <h2 className="text-3xl md:text-5xl font-bold text-white mb-4">My Learning Journey</h2>
            <p className="text-slate-400 max-w-2xl mx-auto">เส้นทางการเรียนรู้ที่ไม่เคยหยุดนิ่ง จากผู้เล่น สู่ผู้สร้าง และผู้แบ่งปัน</p>
          </motion.div>

          <div className="grid md:grid-cols-3 gap-8">
            {/* Step 1 */}
            <motion.div 
              whileHover={{ y: -10, boxShadow: "0 15px 30px -10px rgba(6,182,212,0.3)" }}
              className="group bg-slate-900 border border-slate-800 p-8 rounded-xl relative overflow-hidden hover:border-cyan-500/50 transition-all duration-300 shadow-lg"
            >
              <div className="absolute top-0 left-0 w-full h-1 bg-gradient-to-r from-cyan-500 to-blue-500 transform scale-x-0 group-hover:scale-x-100 transition-transform duration-500 origin-left"></div>
              <div className="mb-6 p-3 bg-slate-800 w-fit rounded-lg text-cyan-500 group-hover:text-cyan-400 group-hover:scale-110 transition-all">
                <Terminal size={32} />
              </div>
              <h3 className="text-xl font-bold text-white mb-3">The Spark: Security & Code</h3>
              <p className="text-slate-400 leading-relaxed">
                เริ่มต้นความสนใจจากการตั้งคำถามว่า "ระบบทำงานอย่างไร?" ฝึกฝนการเขียนภาษา <b>Lua</b> ใน Roblox และศึกษาเรื่อง Cyber Security (Penetration Testing) เพื่อเข้าใจช่องโหว่และการป้องกันระบบ ซึ่งเป็นการปลูกฝัง Mindset ของการคิดอย่างเป็นระบบ
              </p>
            </motion.div>

            {/* Step 2 */}
            <motion.div 
              whileHover={{ y: -10, boxShadow: "0 15px 30px -10px rgba(59,130,246,0.3)" }}
              className="group bg-slate-900 border border-slate-800 p-8 rounded-xl relative overflow-hidden hover:border-blue-500/50 transition-all duration-300 shadow-lg"
            >
              <div className="absolute top-0 left-0 w-full h-1 bg-gradient-to-r from-blue-500 to-purple-500 transform scale-x-0 group-hover:scale-x-100 transition-transform duration-500 origin-left"></div>
              <div className="mb-6 p-3 bg-slate-800 w-fit rounded-lg text-blue-500 group-hover:text-blue-400 group-hover:scale-110 transition-all">
                <Globe size={32} />
              </div>
              <h3 className="text-xl font-bold text-white mb-3">The Builder: Web Development</h3>
              <p className="text-slate-400 leading-relaxed">
                ต่อยอดสู่การลงมือทำจริง โดยการพัฒนาเว็บไซต์ Download Hub ด้วยตนเอง เรียนรู้ HTML, CSS และการจัดการ Server เพื่อแก้ปัญหาการเข้าถึงไฟล์ Mod เกมที่ยุ่งยาก ให้กลายเป็นเรื่องง่ายสำหรับผู้ใช้ทั่วไป
              </p>
            </motion.div>

            {/* Step 3 */}
            <motion.div 
              whileHover={{ y: -10, boxShadow: "0 15px 30px -10px rgba(236,72,153,0.3)" }}
              className="group bg-slate-900 border border-slate-800 p-8 rounded-xl relative overflow-hidden hover:border-pink-500/50 transition-all duration-300 shadow-lg"
            >
              <div className="absolute top-0 left-0 w-full h-1 bg-gradient-to-r from-purple-500 to-pink-500 transform scale-x-0 group-hover:scale-x-100 transition-transform duration-500 origin-left"></div>
              <div className="mb-6 p-3 bg-slate-800 w-fit rounded-lg text-pink-500 group-hover:text-pink-400 group-hover:scale-110 transition-all">
                <Video size={32} />
              </div>
              <h3 className="text-xl font-bold text-white mb-3">The Educator: Content Creator</h3>
              <p className="text-slate-400 leading-relaxed">
                ค้นพบตัวตนในการเป็น "ผู้ถ่ายทอด" ผ่านการทำช่อง TikTok และดูแล Discord Community สอนเทคนิคการ Mod เกม เปลี่ยนเรื่องเทคนิคที่ซับซ้อนให้สนุกและเข้าใจง่าย นี่คือก้าวแรกสู่การเป็นนักเทคโนโลยีการศึกษา
              </p>
            </motion.div>
          </div>
        </div>
      </section>

      {/* Projects/Portfolio Section */}
      <section id="projects" className="py-24 bg-slate-950 relative">
        <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
          <motion.div 
            variants={fadeInUp}
            initial="initial"
            whileInView="animate"
            viewport={{ once: true }}
            className="flex flex-col items-center mb-16"
          >
             <h2 className="text-4xl font-bold text-white mb-4">Featured Projects</h2>
             <div className="h-1 w-24 bg-cyan-500 rounded-full shadow-[0_0_15px_rgba(6,182,212,0.8)]"></div>
             <p className="text-slate-400 mt-4 text-center">ผลงานเชิงประจักษ์ที่แสดงถึงทักษะและความตั้งใจ</p>
          </motion.div>

          <div className="space-y-24">
            
            {/* Project 1: Discord */}
            <motion.div 
              initial={{ opacity: 0, y: 50 }}
              whileInView={{ opacity: 1, y: 0 }}
              viewport={{ once: true, margin: "-100px" }}
              whileHover={{ scale: 1.01 }}
              transition={{ duration: 0.3 }}
              className="flex flex-col md:flex-row gap-8 items-center"
            >
              <div className="w-full md:w-1/2 relative group">
                <div className="absolute inset-0 bg-cyan-500/20 blur-xl opacity-0 group-hover:opacity-100 transition-opacity duration-500"></div>
                <div className="relative bg-slate-900 border border-slate-800 p-8 rounded-xl overflow-hidden group-hover:border-cyan-500/50 transition-colors shadow-lg">
                  <div className="absolute top-0 right-0 p-4 opacity-10 text-cyan-500">
                    <Server size={120} />
                  </div>
                  <Server size={64} className="text-cyan-500 mb-6 group-hover:scale-110 transition-transform" />
                  <h3 className="text-2xl font-bold text-white mb-2">Discord Support Community</h3>
                  <div className="flex gap-2 mb-4">
                     <span className="text-xs font-semibold px-2 py-1 bg-cyan-900/40 text-cyan-300 rounded border border-cyan-700/50">Community Leader</span>
                     <span className="text-xs font-semibold px-2 py-1 bg-slate-800 text-slate-300 rounded border border-slate-700">Entrepreneurship</span>
                  </div>
                  <p className="text-slate-400">บริหารจัดการ Community ขนาดใหญ่ที่มีสมาชิกกว่า 3,000 คน และมีการบริหารจัดการธุรกิจดิจิทัลภายในเซิร์ฟเวอร์</p>
                </div>
              </div>
              <div className="w-full md:w-1/2 md:pl-8 border-l border-slate-800 md:border-l-cyan-900/30">
                 <h3 className="text-3xl font-bold text-white mb-6">Community Management & Entrepreneurship</h3>
                 <p className="text-slate-400 mb-6 leading-relaxed">
                   การดูแลคนจำนวนมากควบคู่ไปกับการบริหารธุรกิจ ทำให้ผมได้ฝึกทักษะการเป็นผู้นำและการจัดการ
                 </p>
                 <ul className="space-y-4 text-slate-300">
                    <li className="flex items-start gap-3 group">
                      <Award size={20} className="text-yellow-400 mt-1 group-hover:scale-125 transition-transform" />
                      <div>
                        <span className="font-semibold text-white group-hover:text-cyan-400 transition-colors">Systematic Support:</span>
                        <p className="text-sm text-slate-400">สร้างระบบ Ticket และใช้ Bot ช่วยจัดการปัญหา User อย่างเป็นระบบ</p>
                      </div>
                    </li>
                    <li className="flex items-start gap-3 group">
                      <ShoppingBag size={20} className="text-yellow-400 mt-1 group-hover:scale-125 transition-transform" />
                      <div>
                        <span className="font-semibold text-white group-hover:text-cyan-400 transition-colors">Digital Commerce:</span>
                        <p className="text-sm text-slate-400">มีการจำหน่ายสินค้าดิจิทัลและบริหารรายได้ภายในเซิร์ฟเวอร์ (รายได้เฉลี่ย 3,000 บาท/เดือน)</p>
                      </div>
                    </li>
                 </ul>
                 <motion.a 
                  href="https://discord.gg/FnmWw7nWyq"
                  target="_blank"
                  rel="noopener noreferrer"
                  whileHover={{ scale: 1.05, boxShadow: "0 0 20px rgba(99,102,241,0.5)" }}
                  whileTap={{ scale: 0.95 }}
                  className="inline-flex items-center gap-2 px-6 py-3 bg-indigo-600 text-white font-bold rounded-lg hover:bg-indigo-500 transition shadow-lg shadow-indigo-500/30 mt-4 border border-transparent hover:border-indigo-300"
                >
                  <Server size={20} />
                  <span>Join Community</span>
                </motion.a>
              </div>
            </motion.div>

             {/* Project 2: TikTok */}
             <motion.div 
              initial={{ opacity: 0, y: 50 }}
              whileInView={{ opacity: 1, y: 0 }}
              viewport={{ once: true, margin: "-100px" }}
              whileHover={{ scale: 1.01 }}
              transition={{ duration: 0.3 }}
              className="flex flex-col md:flex-row-reverse gap-8 items-center"
            >
              <div className="w-full md:w-1/2 relative group">
                <div className="absolute inset-0 bg-pink-500/20 blur-xl opacity-0 group-hover:opacity-100 transition-opacity duration-500"></div>
                <div className="relative bg-slate-900 border border-slate-800 p-8 rounded-xl overflow-hidden group-hover:border-pink-500/50 transition-colors shadow-lg">
                  <div className="absolute top-0 right-0 p-4 opacity-10 text-pink-500">
                    <Video size={120} />
                  </div>
                  <Video size={64} className="text-pink-500 mb-6 group-hover:scale-110 transition-transform" />
                  <h3 className="text-2xl font-bold text-white mb-2">TikTok Education Channel</h3>
                  <div className="flex gap-2 mb-4">
                     <span className="text-xs font-semibold px-2 py-1 bg-pink-900/40 text-pink-300 rounded border border-pink-700/50">Content Creator</span>
                     <span className="text-xs font-semibold px-2 py-1 bg-slate-800 text-slate-300 rounded border border-slate-700">Video Editing</span>
                  </div>
                  <p className="text-slate-400">ช่องให้ความรู้เรื่อง Game Modding ที่มียอดผู้ติดตามกว่า 2,000 คน และยอดวิวเฉลี่ย 10,000+ ต่อคลิป</p>
                </div>
              </div>
              <div className="w-full md:w-1/2 md:pl-8 md:text-right border-l md:border-l-0 md:border-r border-slate-800 md:border-r-pink-900/30 pl-4 md:pl-0 md:pr-4">
                 <h3 className="text-3xl font-bold text-white mb-6">Digital Media for Education</h3>
                 <p className="text-slate-400 mb-6 leading-relaxed">
                   ผมเชื่อในพลังของ "Micro-learning" การย่อยเนื้อหาที่ซับซ้อนให้สั้น กระชับ และสนุก ภายในเวลา 1 นาที
                 </p>
                 <ul className="space-y-4 text-slate-300 flex flex-col md:items-end">
                    <li className="flex items-start gap-3 flex-row-reverse text-right group">
                      <Award size={20} className="text-pink-400 mt-1 group-hover:scale-125 transition-transform" />
                      <div>
                        <span className="font-semibold text-white group-hover:text-pink-400 transition-colors">Complex to Simple:</span>
                        <p className="text-sm text-slate-400">แปลงโค้ด Lua และวิธีการลง Mod ที่ยุ่งยาก ให้เป็นขั้นตอนง่ายๆ</p>
                      </div>
                    </li>
                    <li className="flex items-start gap-3 flex-row-reverse text-right group">
                      <Award size={20} className="text-pink-400 mt-1 group-hover:scale-125 transition-transform" />
                      <div>
                        <span className="font-semibold text-white group-hover:text-pink-400 transition-colors">Engagement:</span>
                        <p className="text-sm text-slate-400">สร้างปฏิสัมพันธ์กับผู้เรียน ตอบคำถาม และรับฟัง Feedback สม่ำเสมอ</p>
                      </div>
                    </li>
                 </ul>
                 <motion.a 
                  href="https://www.tiktok.com/@hengsosleepy?_r=1&_t=ZS-92eXkgMWgDJ"
                  target="_blank"
                  rel="noopener noreferrer"
                  whileHover={{ scale: 1.05, boxShadow: "0 0 20px rgba(219,39,119,0.5)" }}
                  whileTap={{ scale: 0.95 }}
                  className="inline-flex items-center gap-2 px-6 py-3 bg-pink-600 text-white font-bold rounded-lg hover:bg-pink-500 transition shadow-lg shadow-pink-500/30 mt-4 border border-transparent hover:border-pink-300"
                >
                  <ExternalLink size={20} />
                  <span>@hengsosleepy</span>
                </motion.a>
              </div>
            </motion.div>

             {/* Project 3: Web */}
             <motion.div 
              initial={{ opacity: 0, y: 50 }}
              whileInView={{ opacity: 1, y: 0 }}
              viewport={{ once: true, margin: "-100px" }}
              whileHover={{ scale: 1.01 }}
              transition={{ duration: 0.3 }}
              className="flex flex-col md:flex-row gap-8 items-center"
            >
              <div className="w-full md:w-1/2 relative group">
                <div className="absolute inset-0 bg-blue-500/20 blur-xl opacity-0 group-hover:opacity-100 transition-opacity duration-500"></div>
                <div className="relative bg-slate-900 border border-slate-800 p-8 rounded-xl overflow-hidden group-hover:border-blue-500/50 transition-colors shadow-lg">
                  <div className="absolute top-0 right-0 p-4 opacity-10 text-blue-500">
                    <Code size={120} />
                  </div>
                  <Code size={64} className="text-blue-500 mb-6 group-hover:scale-110 transition-transform" />
                  <h3 className="text-2xl font-bold text-white mb-2">Game Mod Download Hub</h3>
                  <div className="flex gap-2 mb-4">
                     <span className="text-xs font-semibold px-2 py-1 bg-blue-900/40 text-blue-300 rounded border border-blue-700/50">Web Development</span>
                     <span className="text-xs font-semibold px-2 py-1 bg-slate-800 text-slate-300 rounded border border-slate-700">UI/UX Design</span>
                  </div>
                  <p className="text-slate-400">เว็บไซต์ส่วนตัวสำหรับรวบรวมและแจกจ่าย Mod เกม ที่พัฒนาขึ้นเองเพื่อแก้ปัญหาลิงก์เสียและความปลอดภัย</p>
                </div>
              </div>
              <div className="w-full md:w-1/2 md:pl-8 border-l border-slate-800 md:border-l-blue-900/30">
                 <h3 className="text-3xl font-bold text-white mb-6">Web Technology & Security</h3>
                 <p className="text-slate-400 mb-6 leading-relaxed">
                   โปรเจกต์ที่ทำให้ผมได้ฝึกทักษะ Full-stack เบื้องต้น และการตระหนักถึงความปลอดภัยของผู้ใช้งาน (User Safety)
                 </p>
                 <ul className="space-y-4 text-slate-300 mb-8">
                    <li className="flex items-start gap-3 group">
                      <Award size={20} className="text-yellow-400 mt-1 group-hover:scale-125 transition-transform" />
                      <div>
                        <span className="font-semibold text-white group-hover:text-blue-400 transition-colors">User-Centric Design:</span>
                        <p className="text-sm text-slate-400">ออกแบบหน้าเว็บให้ใช้งานง่าย ไม่ซับซ้อน รองรับทุกอุปกรณ์ (Responsive)</p>
                      </div>
                    </li>
                    <li className="flex items-start gap-3 group">
                      <Award size={20} className="text-yellow-400 mt-1 group-hover:scale-125 transition-transform" />
                      <div>
                        <span className="font-semibold text-white group-hover:text-blue-400 transition-colors">Security Mindset:</span>
                        <p className="text-sm text-slate-400">ตรวจสอบความปลอดภัยของไฟล์ Mod ก่อนเผยแพร่ เพื่อสร้างความมั่นใจให้ผู้ใช้</p>
                      </div>
                    </li>
                 </ul>
                 
                 <motion.a 
                  href="https://sam-so-sleepy-web2-0-self.vercel.app/"
                  target="_blank"
                  rel="noopener noreferrer"
                  whileHover={{ scale: 1.05, boxShadow: "0 0 20px rgba(37,99,235,0.5)" }}
                  whileTap={{ scale: 0.95 }}
                  className="inline-flex items-center gap-2 px-6 py-3 bg-blue-600 text-white font-bold rounded-lg hover:bg-blue-500 transition shadow-lg shadow-blue-500/30 border border-transparent hover:border-blue-300"
                >
                  <ExternalLink size={20} />
                  <span>Visit Website</span>
                </motion.a>
              </div>
            </motion.div>

          </div>
        </div>
      </section>

      {/* Contact Section */}
      <section id="contact" className="py-24 bg-slate-900 relative border-t border-cyan-900/30">
        <div className="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 text-center relative z-10">
          <motion.div 
            variants={fadeInUp}
            initial="initial"
            whileInView="animate"
            viewport={{ once: true }}
            className="mb-12"
          >
            <h2 className="text-3xl font-bold text-white mb-2">Get In Touch</h2>
            <p className="text-slate-400">พร้อมที่จะเรียนรู้และเติบโต ติดต่อผมได้ที่ช่องทางด้านล่าง</p>
          </motion.div>
          
          <motion.div 
            variants={staggerContainer}
            initial="initial"
            whileInView="animate"
            viewport={{ once: true }}
            className="grid sm:grid-cols-2 md:grid-cols-3 gap-6 mb-16"
          >
            {[
              { icon: Mail, title: "Email", val: "thanakrithbupphathaku", sub: "@gmail.com", link: "mailto:thanakrithbupphathaku@gmail.com", color: "text-cyan-400", border: "hover:border-cyan-500" },
              { icon: Video, title: "TikTok", val: "@hengsosleepy", sub: "Follow Me", link: "https://www.tiktok.com/@hengsosleepy?_r=1&_t=ZS-92eXkgMWgDJ", color: "text-pink-400", border: "hover:border-pink-500" },
              { icon: Server, title: "Discord", val: "Join Server", sub: "Community", link: "https://discord.gg/FnmWw7nWyq", color: "text-blue-400", border: "hover:border-blue-500" }
            ].map((item, index) => (
              <motion.a 
                key={index}
                href={item.link}
                target="_blank"
                rel="noopener noreferrer"
                variants={fadeInUp}
                whileHover={{ y: -5, boxShadow: "0 5px 15px rgba(0,0,0,0.5)" }}
                className={`flex flex-col items-center p-6 bg-slate-950 border border-slate-800 rounded-xl ${item.border} transition-all duration-300 group shadow-md hover:shadow-cyan-500/10`}
              >
                <div className={`p-4 bg-slate-900 rounded-full mb-4 group-hover:bg-slate-800 group-hover:scale-110 transition-all ${item.color}`}>
                  <item.icon size={28} />
                </div>
                <h3 className="font-bold text-white">{item.title}</h3>
                <p className="text-slate-500 text-sm mt-1 group-hover:text-white transition break-all px-2">{item.val}{item.sub && <span className="block text-xs text-slate-600">{item.sub}</span>}</p>
              </motion.a>
            ))}
          </motion.div>

          <motion.div 
            initial={{ opacity: 0, scale: 0.9 }}
            whileInView={{ opacity: 1, scale: 1 }}
            viewport={{ once: true }}
            className="p-10 bg-gradient-to-br from-slate-800 to-slate-900 border border-slate-700 rounded-2xl text-white relative overflow-hidden group shadow-2xl hover:shadow-[0_0_30px_rgba(6,182,212,0.15)] transition-shadow duration-500"
          >
             <div className="absolute inset-0 bg-blue-600/10 mix-blend-overlay"></div>
             <div className="absolute -top-24 -right-24 w-48 h-48 bg-cyan-500/20 rounded-full blur-3xl animate-pulse"></div>
             
             <h3 className="text-2xl font-bold mb-4 relative z-10">พร้อมสำหรับการศึกษาต่อในระดับมหาวิทยาลัย</h3>
             <p className="text-slate-300 mb-8 max-w-2xl mx-auto relative z-10 leading-relaxed">
               ด้วยพื้นฐานทางภาษา ความเชี่ยวชาญด้านเทคโนโลยี และประสบการณ์ในการสร้างสรรค์สื่อการสอน ผมมีความพร้อมและความมุ่งมั่นอย่างเต็มที่ ที่จะเป็นบุคลากรคุณภาพของคณะครุศาสตร์ และเติบโตเป็น "ครูยุคใหม่" ที่สร้างการเปลี่ยนแปลงให้กับการศึกษาไทย
             </p>
             <motion.button 
                whileHover={{ scale: 1.05, boxShadow: "0 0 20px rgba(255,255,255,0.4)" }}
                whileTap={{ scale: 0.95 }}
                className="relative z-10 px-10 py-4 bg-white text-slate-900 font-bold rounded-lg hover:bg-cyan-50 transition shadow-lg flex items-center gap-2 mx-auto"
             >
                <ExternalLink size={20} />
                Download Resume
             </motion.button>
          </motion.div>
        </div>
      </section>

      {/* Footer */}
      <footer className="bg-black text-slate-500 py-8 text-center text-sm border-t border-slate-900 relative z-10">
        <p>&copy; 2024 Thanakrit Bupphataku. Designed with Passion & Code.</p>
      </footer>

    </div>
  );
};

export default Portfolio;
