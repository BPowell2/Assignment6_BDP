


public class DepthFirstSearch {       
       Node root;
       int heightOfTree;
       int numberOfNodesTraversed;
       public DepthFirstSearch()
       {               
                   System.out.println("Call DFS with root node to do a Depth First Search.");
       }//end of DepthFirstSearch
        public void DFS(Node node)        {
        		
        		if (node == null) {
        			return;
        		}//end of if for checking if node is a leaf
        		node.getData();
        			System.out.println("current node = "+node.getData()); 
                   
                  DFS(node.getlChild());
                  DFS(node.getrChild());
                  System.out.println("traversed to next node the current amount of nodes traversed is "+numberOfNodesTraversed+" the height of the tree is");
                  numberOfNodesTraversed ++;
                  
                  //ADD CODE TO TRAVERSE THE TREE HERE
                  //THIS IS APPROXIMATELY THREE LINES OF CODE
                  //INCLUDING AN IF STATEMENT TO
                  //SEE IF THE NODE IS A LEAF
                  //AND TWO RECURSIVE CALLS TO THE CHILDREN

                  //MODIFY OTHER CODE AS NECESSARY

        }//end of DFS

}//end of DepthFirstSearch class
