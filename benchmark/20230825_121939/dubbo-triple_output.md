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
# Warmup Iteration   1: 1.439 ops/ms
# Warmup Iteration   2: 3.429 ops/ms
# Warmup Iteration   3: 6.837 ops/ms
Iteration   1: 7.308 ops/ms
Iteration   2: 7.757 ops/ms
Iteration   3: 7.560 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.542 ±(99.9%) 4.108 ops/ms [Average]
  (min, avg, max) = (7.308, 7.542, 7.757), stdev = 0.225
  CI (99.9%): [3.433, 11.650] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.083 ops/ms
# Warmup Iteration   2: 6.605 ops/ms
# Warmup Iteration   3: 8.099 ops/ms
Iteration   1: 8.237 ops/ms
Iteration   2: 8.118 ops/ms
Iteration   3: 8.208 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.188 ±(99.9%) 1.138 ops/ms [Average]
  (min, avg, max) = (8.118, 8.188, 8.237), stdev = 0.062
  CI (99.9%): [7.050, 9.325] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 2.305 ops/ms
# Warmup Iteration   2: 6.493 ops/ms
# Warmup Iteration   3: 7.581 ops/ms
Iteration   1: 7.859 ops/ms
Iteration   2: 7.898 ops/ms
Iteration   3: 7.656 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.804 ±(99.9%) 2.372 ops/ms [Average]
  (min, avg, max) = (7.656, 7.804, 7.898), stdev = 0.130
  CI (99.9%): [5.433, 10.176] (assumes normal distribution)


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
# Warmup Iteration   1: 1.864 ops/ms
# Warmup Iteration   2: 4.655 ops/ms
# Warmup Iteration   3: 6.423 ops/ms
Iteration   1: 6.518 ops/ms
Iteration   2: 6.391 ops/ms
Iteration   3: 6.631 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.514 ±(99.9%) 2.184 ops/ms [Average]
  (min, avg, max) = (6.391, 6.514, 6.631), stdev = 0.120
  CI (99.9%): [4.330, 8.697] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 13.341 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.966 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.273 ±(99.9%) 0.006 ms/op
Iteration   1: 4.237 ±(99.9%) 0.007 ms/op
Iteration   2: 3.971 ±(99.9%) 0.012 ms/op
Iteration   3: 4.140 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.116 ±(99.9%) 2.452 ms/op [Average]
  (min, avg, max) = (3.971, 4.116, 4.237), stdev = 0.134
  CI (99.9%): [1.664, 6.568] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 11.523 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.290 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.046 ±(99.9%) 0.008 ms/op
Iteration   1: 3.997 ±(99.9%) 0.006 ms/op
Iteration   2: 3.973 ±(99.9%) 0.004 ms/op
Iteration   3: 3.876 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.949 ±(99.9%) 1.166 ms/op [Average]
  (min, avg, max) = (3.876, 3.949, 3.997), stdev = 0.064
  CI (99.9%): [2.783, 5.115] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 13.745 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.889 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.221 ±(99.9%) 0.004 ms/op
Iteration   1: 4.185 ±(99.9%) 0.007 ms/op
Iteration   2: 4.027 ±(99.9%) 0.007 ms/op
Iteration   3: 4.126 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.113 ±(99.9%) 1.455 ms/op [Average]
  (min, avg, max) = (4.027, 4.113, 4.185), stdev = 0.080
  CI (99.9%): [2.658, 5.567] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 14.745 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 5.629 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.979 ±(99.9%) 0.007 ms/op
Iteration   1: 4.906 ±(99.9%) 0.014 ms/op
Iteration   2: 4.822 ±(99.9%) 0.012 ms/op
Iteration   3: 4.803 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.844 ±(99.9%) 0.994 ms/op [Average]
  (min, avg, max) = (4.803, 4.844, 4.906), stdev = 0.054
  CI (99.9%): [3.850, 5.837] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 12.260 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 5.189 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.412 ±(99.9%) 0.018 ms/op
Iteration   1: 4.227 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.999 ms/op
                 createUser·p0.50:   3.990 ms/op
                 createUser·p0.90:   4.850 ms/op
                 createUser·p0.95:   5.734 ms/op
                 createUser·p0.99:   8.536 ms/op
                 createUser·p0.999:  29.214 ms/op
                 createUser·p0.9999: 33.021 ms/op
                 createUser·p1.00:   33.423 ms/op

Iteration   2: 4.111 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.649 ms/op
                 createUser·p0.50:   3.985 ms/op
                 createUser·p0.90:   4.604 ms/op
                 createUser·p0.95:   5.153 ms/op
                 createUser·p0.99:   7.741 ms/op
                 createUser·p0.999:  13.828 ms/op
                 createUser·p0.9999: 30.900 ms/op
                 createUser·p1.00:   31.162 ms/op

Iteration   3: 4.127 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.433 ms/op
                 createUser·p0.50:   3.944 ms/op
                 createUser·p0.90:   4.637 ms/op
                 createUser·p0.95:   5.136 ms/op
                 createUser·p0.99:   8.159 ms/op
                 createUser·p0.999:  29.591 ms/op
                 createUser·p0.9999: 32.791 ms/op
                 createUser·p1.00:   33.489 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 231198
  mean =      4.154 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 232 
    [ 2.500,  5.000) = 215579 
    [ 5.000,  7.500) = 11830 
    [ 7.500, 10.000) = 2585 
    [10.000, 12.500) = 544 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 68 
    [30.000, 32.500) = 117 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.433 ms/op
     p(50.0000) =      3.973 ms/op
     p(90.0000) =      4.710 ms/op
     p(95.0000) =      5.284 ms/op
     p(99.0000) =      8.241 ms/op
     p(99.9000) =     27.027 ms/op
     p(99.9900) =     32.702 ms/op
     p(99.9990) =     33.403 ms/op
     p(99.9999) =     33.489 ms/op
    p(100.0000) =     33.489 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.609 ±(99.9%) 0.186 ms/op
# Warmup Iteration   2: 4.871 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.067 ±(99.9%) 0.012 ms/op
Iteration   1: 4.073 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.409 ms/op
                 existUser·p0.50:   3.805 ms/op
                 existUser·p0.90:   4.997 ms/op
                 existUser·p0.95:   5.784 ms/op
                 existUser·p0.99:   8.225 ms/op
                 existUser·p0.999:  13.393 ms/op
                 existUser·p0.9999: 23.233 ms/op
                 existUser·p1.00:   24.674 ms/op

Iteration   2: 4.051 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   2.175 ms/op
                 existUser·p0.50:   3.879 ms/op
                 existUser·p0.90:   4.801 ms/op
                 existUser·p0.95:   5.480 ms/op
                 existUser·p0.99:   7.176 ms/op
                 existUser·p0.999:  12.116 ms/op
                 existUser·p0.9999: 26.494 ms/op
                 existUser·p1.00:   27.689 ms/op

Iteration   3: 4.083 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.692 ms/op
                 existUser·p0.50:   3.822 ms/op
                 existUser·p0.90:   4.538 ms/op
                 existUser·p0.95:   5.808 ms/op
                 existUser·p0.99:   8.438 ms/op
                 existUser·p0.999:  27.285 ms/op
                 existUser·p0.9999: 31.075 ms/op
                 existUser·p1.00:   31.916 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 235817
  mean =      4.069 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 294 
    [ 2.500,  5.000) = 216199 
    [ 5.000,  7.500) = 15683 
    [ 7.500, 10.000) = 2516 
    [10.000, 12.500) = 722 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.409 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.760 ms/op
     p(95.0000) =      5.693 ms/op
     p(99.0000) =      8.036 ms/op
     p(99.9000) =     20.400 ms/op
     p(99.9900) =     30.193 ms/op
     p(99.9990) =     31.708 ms/op
     p(99.9999) =     31.916 ms/op
    p(100.0000) =     31.916 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 11.863 ±(99.9%) 0.205 ms/op
# Warmup Iteration   2: 4.665 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.489 ±(99.9%) 0.018 ms/op
Iteration   1: 4.440 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.065 ms/op
                 getUser·p0.50:   4.059 ms/op
                 getUser·p0.90:   5.292 ms/op
                 getUser·p0.95:   6.939 ms/op
                 getUser·p0.99:   9.764 ms/op
                 getUser·p0.999:  24.347 ms/op
                 getUser·p0.9999: 26.371 ms/op
                 getUser·p1.00:   27.132 ms/op

Iteration   2: 4.078 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.413 ms/op
                 getUser·p0.50:   3.969 ms/op
                 getUser·p0.90:   4.604 ms/op
                 getUser·p0.95:   4.973 ms/op
                 getUser·p0.99:   6.914 ms/op
                 getUser·p0.999:  12.450 ms/op
                 getUser·p0.9999: 27.536 ms/op
                 getUser·p1.00:   27.984 ms/op

Iteration   3: 4.230 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.917 ms/op
                 getUser·p0.50:   4.043 ms/op
                 getUser·p0.90:   4.760 ms/op
                 getUser·p0.95:   5.300 ms/op
                 getUser·p0.99:   7.979 ms/op
                 getUser·p0.999:  18.679 ms/op
                 getUser·p0.9999: 35.783 ms/op
                 getUser·p1.00:   36.372 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 226134
  mean =      4.244 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 61 
    [ 2.500,  5.000) = 207131 
    [ 5.000,  7.500) = 14522 
    [ 7.500, 10.000) = 3253 
    [10.000, 12.500) = 762 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 87 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      4.018 ms/op
     p(90.0000) =      4.874 ms/op
     p(95.0000) =      5.538 ms/op
     p(99.0000) =      8.847 ms/op
     p(99.9000) =     20.898 ms/op
     p(99.9900) =     34.024 ms/op
     p(99.9990) =     36.093 ms/op
     p(99.9999) =     36.372 ms/op
    p(100.0000) =     36.372 ms/op


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
# Warmup Iteration   1: 13.863 ±(99.9%) 0.198 ms/op
# Warmup Iteration   2: 5.391 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.953 ±(99.9%) 0.018 ms/op
Iteration   1: 4.816 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.097 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.341 ms/op
                 listUser·p0.95:   5.998 ms/op
                 listUser·p0.99:   9.290 ms/op
                 listUser·p0.999:  24.379 ms/op
                 listUser·p0.9999: 26.837 ms/op
                 listUser·p1.00:   27.591 ms/op

Iteration   2: 4.667 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.442 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   8.569 ms/op
                 listUser·p0.999:  19.988 ms/op
                 listUser·p0.9999: 25.632 ms/op
                 listUser·p1.00:   26.706 ms/op

Iteration   3: 4.955 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.702 ms/op
                 listUser·p0.50:   4.661 ms/op
                 listUser·p0.90:   5.538 ms/op
                 listUser·p0.95:   7.307 ms/op
                 listUser·p0.99:   9.585 ms/op
                 listUser·p0.999:  17.465 ms/op
                 listUser·p0.9999: 21.663 ms/op
                 listUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 199453
  mean =      4.810 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 164657 
    [ 5.000,  7.500) = 28776 
    [ 7.500, 10.000) = 4465 
    [10.000, 12.500) = 842 
    [12.500, 15.000) = 249 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 119 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 102 
    [25.000, 27.500) = 52 

  Percentiles, ms/op:
      p(0.0000) =      1.442 ms/op
     p(50.0000) =      4.588 ms/op
     p(90.0000) =      5.333 ms/op
     p(95.0000) =      6.038 ms/op
     p(99.0000) =      9.273 ms/op
     p(99.9000) =     21.022 ms/op
     p(99.9900) =     26.247 ms/op
     p(99.9990) =     27.297 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.542 ± 4.108  ops/ms
ClientPb.existUser                       thrpt       3   8.188 ± 1.138  ops/ms
ClientPb.getUser                         thrpt       3   7.804 ± 2.372  ops/ms
ClientPb.listUser                        thrpt       3   6.514 ± 2.184  ops/ms
ClientPb.createUser                       avgt       3   4.116 ± 2.452   ms/op
ClientPb.existUser                        avgt       3   3.949 ± 1.166   ms/op
ClientPb.getUser                          avgt       3   4.113 ± 1.455   ms/op
ClientPb.listUser                         avgt       3   4.844 ± 0.994   ms/op
ClientPb.createUser                     sample  231198   4.154 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.433           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.973           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.710           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.284           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.241           ms/op
ClientPb.createUser:createUser·p0.999   sample          27.027           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.702           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.489           ms/op
ClientPb.existUser                      sample  235817   4.069 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.409           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.850           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.760           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.693           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.036           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.400           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.193           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.916           ms/op
ClientPb.getUser                        sample  226134   4.244 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.065           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.018           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.874           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.538           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.847           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.898           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.024           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.372           ms/op
ClientPb.listUser                       sample  199453   4.810 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.442           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.588           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.333           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.038           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.273           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.022           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.247           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.591           ms/op
