/* Import Poppins font */
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');

.layout-container {
  display: flex;
  min-height: 100vh;
  background-color: #253f21 !important;
  padding: 1.5rem 2rem 3rem 2rem; /* Reduced bottom padding to match main content */
  font-family: 'Poppins', sans-serif;
  gap: 2rem;
}

/* Main Content Area */
.main-content {
  flex: 1;
  background-color: #ffffff;
  border-radius: 25px;
  padding: 2rem;
  box-shadow: 0 6px 16px rgba(0, 0, 0, 0.1);
  overflow-y: auto;
  overflow-x: hidden;
  max-height: calc(100vh - 4rem); /* Adjusted from 6rem to 3rem for more content space */
  margin-bottom: 2rem;
  scrollbar-color: #253f21 #f1f5f9;
}

/* Custom Scrollbar Styling */
.main-content::-webkit-scrollbar {
  width: 8px;
}

.main-content::-webkit-scrollbar-track {
  background: #f1f5f9;
  border-radius: 10px;
}

.main-content::-webkit-scrollbar-thumb {
  background: #253f21;
  border-radius: 10px;
}

.main-content::-webkit-scrollbar-thumb:hover {
  background: #4e7948;
}

.dashboard-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding-bottom: 1.5rem;
  margin-bottom: 1rem; /* Increased from 3rem to create more space */
  border-bottom: 1px solid #e2e8f0;
}

.dashboard-left {
  display: flex;
  align-items: center;  
  gap: 1rem;
}

.sidebar-toggle-inside {
  background-color: #f1f5f9;
  border: none;
  border-radius: 10px;
  padding: 0.5rem 0.6rem;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 1.2rem;
  color: #253f21;
  cursor: pointer;
  transition: background-color 0.2s ease;
}

.sidebar-toggle-inside:hover {
  background-color: #e2e8f0;
}

.dashboard-title {
  font-size: 1.6rem;
  font-weight: 600;
  color: #0f172a;
  font-family: 'Poppins', sans-serif;
}

.current-date {
  font-size: 0.95rem;
  color: #253f21;
  font-weight: 400;
  font-family: 'Poppins', sans-serif;
}

h2, h3 {
  font-family: 'Poppins', sans-serif;
  font-weight: 600;
}

p, td, th {
  font-family: 'Poppins', sans-serif;
  font-weight: 400;
}

/* Responsive About Us Section */
.about-us {
  background-color: #fff;
  padding: clamp(0.75rem, 2vw, 1.5rem);
  border-radius: clamp(20px, 3vw, 35px);
  margin: -1.75rem auto clamp(-1.75rem, -3vw, -1rem) auto;
  box-shadow: 0 4px 5px rgba(0, 0, 0, 0.15);
  border: 2px solid #878787;
  border-left: clamp(5px, 2vw, 9px) solid #878787;
  max-width: 1150px;
  width: clamp(90%, 95%, 100%);
  text-align: center;
}

.about-us h2 {
  text-align: center;
  margin-bottom: 0.25rem;
  font-size: clamp(18px, 3vw, 23px);
  color: #4d4d4d;
  line-height: 1.3;
}

.about-us p {
  text-align: center;
  line-height: 1.6;
  padding: 0 clamp(0.5rem, 3vw, 1.5rem);
  font-size: clamp(14px, 2vw, 16px);
  margin-bottom: clamp(0.25rem, 1vw, 0.75rem);
}

/* Clearance and Membership Section */
.clearance-membership-section {
  display: flex;
  flex-wrap: wrap;
  gap: 2rem;
  margin-top: 2rem;
  margin-bottom: 2rem;
}

/* Shared Card Design for Both Sections */
.clearance-section {
  background-color: #fff;
  padding: 1.5rem;
  border-radius: 35px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.06);
  border: 2px solid #Fd8443;
  border-left: 9px solid #Fd8443;
  flex: 1;
  min-width: 300px;
  height: 90%;
}

.membership-section {
  background-color: #fff;
  padding: 1.5rem;
  border-radius: 35px !important;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.06);
  border: 2px solid #4e7948; /* Added full border */
  border-left: 9px solid #4e7948 !important; 
  flex: 1;
  min-width: 300px;
  height: 90%;
}

.clearance-table,
.membership-table {
  width: 100%;
  border-collapse: collapse;
  margin-top: 1rem;
  font-family: 'Poppins', sans-serif;
}

.clearance-table th,
.clearance-table td,
.membership-table th,
.membership-table td {
  padding: 0.75rem;
  border: 1px solid #ddd;
  text-align: left;
}

.clearance-table th,
.membership-table th {
  background-color: #f0f4f8;
  font-weight: 500;
}
.clearance-table tr:nth-child(even),
.membership-table tr:nth-child(even) {
  background-color: #f8fafc;
}

.membership-section p {
  color: #555;
}

/* Loading and Error Message Styling */
.loading {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  background-color: #3B4E38;
}

.error-message {
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #fff3f3;
  color: #d32f2f;
  padding: 2rem;
  border-radius: 10px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.08);
}

/* Add clickable overlay to close sidebar when clicking outside */
.sidebar-overlay {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: 999; /* Just below sidebar (1000) */
  display: none;
  opacity: 0;
  transition: opacity 0.3s ease;
  background-color: transparent; /* Completely transparent */
  cursor: pointer;
}

/* Show overlay when sidebar is open */
.sidebar-open .sidebar-overlay {
  display: block;
  opacity: 1;
}

/* Responsive Design */
@media (max-width: 768px) {
  .layout-container {
    flex-direction: column;
    padding: 1rem;
  }

  .clearance-membership-section {
    flex-direction: column;
  }

  /* For proper layering when in touch devices */
  .sidebar-overlay {
    -webkit-tap-highlight-color: transparent; /* Remove tap highlight on mobile */
  }
}

/* Media queries for better responsiveness on very small screens */
@media (max-width: 480px) {
  .about-us {
    padding: 0.75rem;
    border-radius: 20px;
    border-left-width: 6px;
    margin-top: -1rem;
    margin-bottom: -0.5rem;
  }
  
  .about-us p {
    padding: 0 0.5rem;
  }
}

@media (max-width: 350px) {
  .about-us {
    padding: 0.5rem;
    border-radius: 15px;
    border-left-width: 5px;
  }
  
  .about-us h2 {
    margin-top: 0.25rem;
  }
}
