# Fullwidth
Grid with full width each column 

 three full width  column wise the main divided into three grid with the following fraction

 main
 {
  display: grid;
  grid-template-columns: 1.2fr 1fr 1fr;
  min-height: 100%;
   }

each column has two row inside with different fraction 
.panel.about {
  grid-template-rows: 3fr 1fr;
  overflow: hidden;
  min-width: 100%;
  min-height: 100%;
}
