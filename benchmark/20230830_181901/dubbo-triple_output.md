# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.503 ops/ms
# Warmup Iteration   2: 3.113 ops/ms
# Warmup Iteration   3: 6.397 ops/ms
Iteration   1: 6.961 ops/ms
Iteration   2: 7.562 ops/ms
Iteration   3: 7.372 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.299 ±(99.9%) 5.605 ops/ms [Average]
  (min, avg, max) = (6.961, 7.299, 7.562), stdev = 0.307
  CI (99.9%): [1.693, 12.904] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.872 ops/ms
# Warmup Iteration   2: 5.342 ops/ms
# Warmup Iteration   3: 7.213 ops/ms
Iteration   1: 7.679 ops/ms
Iteration   2: 7.990 ops/ms
Iteration   3: 7.498 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.722 ±(99.9%) 4.541 ops/ms [Average]
  (min, avg, max) = (7.498, 7.722, 7.990), stdev = 0.249
  CI (99.9%): [3.181, 12.263] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.186 ops/ms
# Warmup Iteration   2: 6.137 ops/ms
# Warmup Iteration   3: 6.758 ops/ms
Iteration   1: 7.573 ops/ms
Iteration   2: 7.696 ops/ms
Iteration   3: 7.409 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.559 ±(99.9%) 2.628 ops/ms [Average]
  (min, avg, max) = (7.409, 7.559, 7.696), stdev = 0.144
  CI (99.9%): [4.931, 10.187] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.104 ops/ms
# Warmup Iteration   2: 5.122 ops/ms
# Warmup Iteration   3: 6.151 ops/ms
Iteration   1: 5.803 ops/ms
Iteration   2: 5.943 ops/ms
Iteration   3: 5.853 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.866 ±(99.9%) 1.295 ops/ms [Average]
  (min, avg, max) = (5.803, 5.866, 5.943), stdev = 0.071
  CI (99.9%): [4.571, 7.162] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 15.543 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 5.910 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.816 ±(99.9%) 0.006 ms/op
Iteration   1: 4.350 ±(99.9%) 0.013 ms/op
Iteration   2: 4.113 ±(99.9%) 0.006 ms/op
Iteration   3: 4.284 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.249 ±(99.9%) 2.233 ms/op [Average]
  (min, avg, max) = (4.113, 4.249, 4.350), stdev = 0.122
  CI (99.9%): [2.016, 6.482] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 13.280 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 5.059 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.080 ±(99.9%) 0.005 ms/op
Iteration   1: 4.012 ±(99.9%) 0.005 ms/op
Iteration   2: 4.073 ±(99.9%) 0.008 ms/op
Iteration   3: 4.124 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.070 ±(99.9%) 1.025 ms/op [Average]
  (min, avg, max) = (4.012, 4.070, 4.124), stdev = 0.056
  CI (99.9%): [3.044, 5.095] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 12.746 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.997 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.509 ±(99.9%) 0.005 ms/op
Iteration   1: 4.070 ±(99.9%) 0.008 ms/op
Iteration   2: 4.323 ±(99.9%) 0.004 ms/op
Iteration   3: 4.063 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.152 ±(99.9%) 2.704 ms/op [Average]
  (min, avg, max) = (4.063, 4.152, 4.323), stdev = 0.148
  CI (99.9%): [1.448, 6.856] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 15.588 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 5.916 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.079 ±(99.9%) 0.006 ms/op
Iteration   1: 5.183 ±(99.9%) 0.005 ms/op
Iteration   2: 5.016 ±(99.9%) 0.007 ms/op
Iteration   3: 5.279 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.159 ±(99.9%) 2.430 ms/op [Average]
  (min, avg, max) = (5.016, 5.159, 5.279), stdev = 0.133
  CI (99.9%): [2.730, 7.589] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 15.017 ±(99.9%) 0.240 ms/op
# Warmup Iteration   2: 5.386 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.737 ±(99.9%) 0.021 ms/op
Iteration   1: 4.385 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.021 ms/op
                 createUser·p0.50:   4.112 ms/op
                 createUser·p0.90:   5.366 ms/op
                 createUser·p0.95:   6.390 ms/op
                 createUser·p0.99:   8.782 ms/op
                 createUser·p0.999:  15.630 ms/op
                 createUser·p0.9999: 32.857 ms/op
                 createUser·p1.00:   33.260 ms/op

Iteration   2: 4.535 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.952 ms/op
                 createUser·p0.50:   4.116 ms/op
                 createUser·p0.90:   5.939 ms/op
                 createUser·p0.95:   7.029 ms/op
                 createUser·p0.99:   10.256 ms/op
                 createUser·p0.999:  31.162 ms/op
                 createUser·p0.9999: 32.996 ms/op
                 createUser·p1.00:   35.717 ms/op

Iteration   3: 4.240 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.663 ms/op
                 createUser·p0.50:   3.977 ms/op
                 createUser·p0.90:   4.981 ms/op
                 createUser·p0.95:   6.029 ms/op
                 createUser·p0.99:   8.684 ms/op
                 createUser·p0.999:  14.702 ms/op
                 createUser·p0.9999: 44.368 ms/op
                 createUser·p1.00:   45.220 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 218954
  mean =      4.383 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 187679 
    [ 5.000, 10.000) = 29744 
    [10.000, 15.000) = 1223 
    [15.000, 20.000) = 62 
    [20.000, 25.000) = 22 
    [25.000, 30.000) = 20 
    [30.000, 35.000) = 145 
    [35.000, 40.000) = 27 
    [40.000, 45.000) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.663 ms/op
     p(50.0000) =      4.071 ms/op
     p(90.0000) =      5.407 ms/op
     p(95.0000) =      6.496 ms/op
     p(99.0000) =      9.224 ms/op
     p(99.9000) =     28.936 ms/op
     p(99.9900) =     42.736 ms/op
     p(99.9990) =     44.683 ms/op
     p(99.9999) =     45.220 ms/op
    p(100.0000) =     45.220 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 12.221 ±(99.9%) 0.172 ms/op
# Warmup Iteration   2: 5.349 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.312 ±(99.9%) 0.016 ms/op
Iteration   1: 4.253 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.898 ms/op
                 existUser·p0.50:   3.883 ms/op
                 existUser·p0.90:   5.374 ms/op
                 existUser·p0.95:   6.463 ms/op
                 existUser·p0.99:   8.929 ms/op
                 existUser·p0.999:  15.417 ms/op
                 existUser·p0.9999: 31.223 ms/op
                 existUser·p1.00:   32.408 ms/op

Iteration   2: 4.183 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.704 ms/op
                 existUser·p0.50:   3.871 ms/op
                 existUser·p0.90:   5.054 ms/op
                 existUser·p0.95:   6.259 ms/op
                 existUser·p0.99:   9.724 ms/op
                 existUser·p0.999:  18.973 ms/op
                 existUser·p0.9999: 37.205 ms/op
                 existUser·p1.00:   38.339 ms/op

Iteration   3: 4.247 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.751 ms/op
                 existUser·p0.50:   3.916 ms/op
                 existUser·p0.90:   5.226 ms/op
                 existUser·p0.95:   6.480 ms/op
                 existUser·p0.99:   9.470 ms/op
                 existUser·p0.999:  15.839 ms/op
                 existUser·p0.9999: 39.256 ms/op
                 existUser·p1.00:   41.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 226941
  mean =      4.228 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 199623 
    [ 5.000, 10.000) = 25588 
    [10.000, 15.000) = 1339 
    [15.000, 20.000) = 199 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 39 
    [30.000, 35.000) = 57 
    [35.000, 40.000) = 91 
    [40.000, 45.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.704 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      5.243 ms/op
     p(95.0000) =      6.390 ms/op
     p(99.0000) =      9.372 ms/op
     p(99.9000) =     17.367 ms/op
     p(99.9900) =     38.535 ms/op
     p(99.9990) =     41.419 ms/op
     p(99.9999) =     41.878 ms/op
    p(100.0000) =     41.878 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 12.580 ±(99.9%) 0.242 ms/op
# Warmup Iteration   2: 5.395 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.473 ±(99.9%) 0.019 ms/op
Iteration   1: 4.433 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.257 ms/op
                 getUser·p0.50:   4.096 ms/op
                 getUser·p0.90:   5.439 ms/op
                 getUser·p0.95:   6.701 ms/op
                 getUser·p0.99:   9.679 ms/op
                 getUser·p0.999:  28.467 ms/op
                 getUser·p0.9999: 32.564 ms/op
                 getUser·p1.00:   33.161 ms/op

Iteration   2: 4.263 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.179 ms/op
                 getUser·p0.50:   3.985 ms/op
                 getUser·p0.90:   4.817 ms/op
                 getUser·p0.95:   5.882 ms/op
                 getUser·p0.99:   10.334 ms/op
                 getUser·p0.999:  27.357 ms/op
                 getUser·p0.9999: 32.555 ms/op
                 getUser·p1.00:   33.554 ms/op

Iteration   3: 4.185 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.413 ms/op
                 getUser·p0.50:   3.994 ms/op
                 getUser·p0.90:   4.915 ms/op
                 getUser·p0.95:   5.603 ms/op
                 getUser·p0.99:   8.009 ms/op
                 getUser·p0.999:  13.746 ms/op
                 getUser·p0.9999: 33.882 ms/op
                 getUser·p1.00:   35.324 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 223681
  mean =      4.291 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 199833 
    [ 5.000,  7.500) = 18628 
    [ 7.500, 10.000) = 3528 
    [10.000, 12.500) = 826 
    [12.500, 15.000) = 460 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 95 
    [30.000, 32.500) = 77 
    [32.500, 35.000) = 48 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.257 ms/op
     p(50.0000) =      4.018 ms/op
     p(90.0000) =      5.071 ms/op
     p(95.0000) =      6.111 ms/op
     p(99.0000) =      9.175 ms/op
     p(99.9000) =     27.448 ms/op
     p(99.9900) =     33.498 ms/op
     p(99.9990) =     34.953 ms/op
     p(99.9999) =     35.324 ms/op
    p(100.0000) =     35.324 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 17.538 ±(99.9%) 0.294 ms/op
# Warmup Iteration   2: 6.944 ±(99.9%) 0.051 ms/op
# Warmup Iteration   3: 5.350 ±(99.9%) 0.024 ms/op
Iteration   1: 5.075 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   0.482 ms/op
                 listUser·p0.50:   4.751 ms/op
                 listUser·p0.90:   5.915 ms/op
                 listUser·p0.95:   7.471 ms/op
                 listUser·p0.99:   10.513 ms/op
                 listUser·p0.999:  28.179 ms/op
                 listUser·p0.9999: 31.841 ms/op
                 listUser·p1.00:   32.309 ms/op

Iteration   2: 5.104 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.247 ms/op
                 listUser·p0.50:   4.768 ms/op
                 listUser·p0.90:   5.865 ms/op
                 listUser·p0.95:   7.307 ms/op
                 listUser·p0.99:   10.846 ms/op
                 listUser·p0.999:  29.655 ms/op
                 listUser·p0.9999: 33.249 ms/op
                 listUser·p1.00:   34.800 ms/op

Iteration   3: 5.060 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.589 ms/op
                 listUser·p0.50:   4.751 ms/op
                 listUser·p0.90:   5.669 ms/op
                 listUser·p0.95:   7.299 ms/op
                 listUser·p0.99:   11.341 ms/op
                 listUser·p0.999:  20.349 ms/op
                 listUser·p0.9999: 25.255 ms/op
                 listUser·p1.00:   25.756 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 188878
  mean =      5.080 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 132967 
    [ 5.000,  7.500) = 47033 
    [ 7.500, 10.000) = 6138 
    [10.000, 12.500) = 1631 
    [12.500, 15.000) = 522 
    [15.000, 17.500) = 155 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 76 
    [30.000, 32.500) = 58 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.482 ms/op
     p(50.0000) =      4.751 ms/op
     p(90.0000) =      5.833 ms/op
     p(95.0000) =      7.365 ms/op
     p(99.0000) =     10.846 ms/op
     p(99.9000) =     26.739 ms/op
     p(99.9900) =     32.575 ms/op
     p(99.9990) =     34.101 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.299 ± 5.605  ops/ms
ClientPb.existUser                       thrpt       3   7.722 ± 4.541  ops/ms
ClientPb.getUser                         thrpt       3   7.559 ± 2.628  ops/ms
ClientPb.listUser                        thrpt       3   5.866 ± 1.295  ops/ms
ClientPb.createUser                       avgt       3   4.249 ± 2.233   ms/op
ClientPb.existUser                        avgt       3   4.070 ± 1.025   ms/op
ClientPb.getUser                          avgt       3   4.152 ± 2.704   ms/op
ClientPb.listUser                         avgt       3   5.159 ± 2.430   ms/op
ClientPb.createUser                     sample  218954   4.383 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.663           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.071           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.407           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.496           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.224           ms/op
ClientPb.createUser:createUser·p0.999   sample          28.936           ms/op
ClientPb.createUser:createUser·p0.9999  sample          42.736           ms/op
ClientPb.createUser:createUser·p1.00    sample          45.220           ms/op
ClientPb.existUser                      sample  226941   4.228 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.704           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.895           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.243           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.390           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.372           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.367           ms/op
ClientPb.existUser:existUser·p0.9999    sample          38.535           ms/op
ClientPb.existUser:existUser·p1.00      sample          41.878           ms/op
ClientPb.getUser                        sample  223681   4.291 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.257           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.018           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.071           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.111           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.175           ms/op
ClientPb.getUser:getUser·p0.999         sample          27.448           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.498           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.324           ms/op
ClientPb.listUser                       sample  188878   5.080 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.482           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.751           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.833           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.365           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.846           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.739           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.575           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.800           ms/op
