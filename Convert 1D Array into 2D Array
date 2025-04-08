def construct2DArray(self, original: List[int], m: int, n: int) -> List[List[int]]:
        if len(original) != m * n:
            return [] 
        new=[[0 for _ in range(n)] for _ in range(m)]
        for i in range(m):
            for j in range(n):
                new[i][j]=original[i*n+j]
        return new
        
