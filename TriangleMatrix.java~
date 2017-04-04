import java.io.*;
import java.util.*;

public class TriangleMatrix extends Matrix{

    public TriangleMatrix(){
	super();
    }

    public TriangleMatrix(double[][] x){
	super(x);
    }

    public TriangleMatrix(TriangleMatrix T){
	super();
    }
    
    public void addTriangle(double x1, double y1, double z1, double x2, double y2, double z2, double x3, double y3, double z3){
	double [] P1 = {x1, y1, z1, 1};
	double [] P2 = {x2, y2, z2, 1};
	double [] P3 = {x3, y3, z3, 1};
	addColumn(P1);
	addColumn(P2);
	addColumn(P3);
    }

}
