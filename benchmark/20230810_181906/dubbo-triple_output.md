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
# Warmup Iteration   1: 1.097 ops/ms
# Warmup Iteration   2: 2.574 ops/ms
# Warmup Iteration   3: 5.540 ops/ms
Iteration   1: 5.717 ops/ms
Iteration   2: 6.148 ops/ms
Iteration   3: 6.177 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.014 ±(99.9%) 4.703 ops/ms [Average]
  (min, avg, max) = (5.717, 6.014, 6.177), stdev = 0.258
  CI (99.9%): [1.311, 10.717] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.826 ops/ms
# Warmup Iteration   2: 5.451 ops/ms
# Warmup Iteration   3: 6.349 ops/ms
Iteration   1: 6.581 ops/ms
Iteration   2: 6.493 ops/ms
Iteration   3: 6.656 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.577 ±(99.9%) 1.493 ops/ms [Average]
  (min, avg, max) = (6.493, 6.577, 6.656), stdev = 0.082
  CI (99.9%): [5.084, 8.069] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.728 ops/ms
# Warmup Iteration   2: 5.091 ops/ms
# Warmup Iteration   3: 6.092 ops/ms
Iteration   1: 6.055 ops/ms
Iteration   2: 6.227 ops/ms
Iteration   3: 6.262 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.182 ±(99.9%) 2.019 ops/ms [Average]
  (min, avg, max) = (6.055, 6.182, 6.262), stdev = 0.111
  CI (99.9%): [4.162, 8.201] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 1.654 ops/ms
# Warmup Iteration   2: 4.063 ops/ms
# Warmup Iteration   3: 5.135 ops/ms
Iteration   1: 5.090 ops/ms
Iteration   2: 5.105 ops/ms
Iteration   3: 5.224 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.140 ±(99.9%) 1.335 ops/ms [Average]
  (min, avg, max) = (5.090, 5.140, 5.224), stdev = 0.073
  CI (99.9%): [3.805, 6.475] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 15.827 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 6.060 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.777 ±(99.9%) 0.008 ms/op
Iteration   1: 5.010 ±(99.9%) 0.012 ms/op
Iteration   2: 5.168 ±(99.9%) 0.011 ms/op
Iteration   3: 5.083 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.087 ±(99.9%) 1.436 ms/op [Average]
  (min, avg, max) = (5.010, 5.087, 5.168), stdev = 0.079
  CI (99.9%): [3.651, 6.523] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 15.383 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 5.474 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.209 ±(99.9%) 0.005 ms/op
Iteration   1: 4.881 ±(99.9%) 0.005 ms/op
Iteration   2: 5.071 ±(99.9%) 0.005 ms/op
Iteration   3: 4.777 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.910 ±(99.9%) 2.717 ms/op [Average]
  (min, avg, max) = (4.777, 4.910, 5.071), stdev = 0.149
  CI (99.9%): [2.193, 7.627] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 15.891 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 5.557 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.273 ±(99.9%) 0.009 ms/op
Iteration   1: 5.378 ±(99.9%) 0.006 ms/op
Iteration   2: 5.036 ±(99.9%) 0.008 ms/op
Iteration   3: 4.968 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.127 ±(99.9%) 4.005 ms/op [Average]
  (min, avg, max) = (4.968, 5.127, 5.378), stdev = 0.220
  CI (99.9%): [1.122, 9.133] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 18.127 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 6.954 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.942 ±(99.9%) 0.015 ms/op
Iteration   1: 6.025 ±(99.9%) 0.014 ms/op
Iteration   2: 5.972 ±(99.9%) 0.019 ms/op
Iteration   3: 6.088 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.028 ±(99.9%) 1.054 ms/op [Average]
  (min, avg, max) = (5.972, 6.028, 6.088), stdev = 0.058
  CI (99.9%): [4.975, 7.082] (assumes normal distribution)


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
# Warmup Iteration   1: 16.718 ±(99.9%) 0.280 ms/op
# Warmup Iteration   2: 6.870 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.787 ±(99.9%) 0.026 ms/op
Iteration   1: 5.234 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.372 ms/op
                 createUser·p0.50:   5.005 ms/op
                 createUser·p0.90:   6.316 ms/op
                 createUser·p0.95:   7.012 ms/op
                 createUser·p0.99:   9.699 ms/op
                 createUser·p0.999:  24.016 ms/op
                 createUser·p0.9999: 27.318 ms/op
                 createUser·p1.00:   28.410 ms/op

Iteration   2: 5.147 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.245 ms/op
                 createUser·p0.50:   4.915 ms/op
                 createUser·p0.90:   6.185 ms/op
                 createUser·p0.95:   7.029 ms/op
                 createUser·p0.99:   9.372 ms/op
                 createUser·p0.999:  25.604 ms/op
                 createUser·p0.9999: 31.588 ms/op
                 createUser·p1.00:   34.079 ms/op

Iteration   3: 5.203 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.302 ms/op
                 createUser·p0.50:   4.915 ms/op
                 createUser·p0.90:   6.513 ms/op
                 createUser·p0.95:   7.299 ms/op
                 createUser·p0.99:   9.765 ms/op
                 createUser·p0.999:  26.673 ms/op
                 createUser·p0.9999: 34.144 ms/op
                 createUser·p1.00:   34.996 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 184729
  mean =      5.194 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 99945 
    [ 5.000,  7.500) = 77683 
    [ 7.500, 10.000) = 5608 
    [10.000, 12.500) = 1008 
    [12.500, 15.000) = 225 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 49 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.245 ms/op
     p(50.0000) =      4.940 ms/op
     p(90.0000) =      6.324 ms/op
     p(95.0000) =      7.152 ms/op
     p(99.0000) =      9.634 ms/op
     p(99.9000) =     24.299 ms/op
     p(99.9900) =     32.606 ms/op
     p(99.9990) =     34.941 ms/op
     p(99.9999) =     34.996 ms/op
    p(100.0000) =     34.996 ms/op


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
# Warmup Iteration   1: 14.091 ±(99.9%) 0.203 ms/op
# Warmup Iteration   2: 5.601 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.052 ±(99.9%) 0.018 ms/op
Iteration   1: 4.879 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.937 ms/op
                 existUser·p0.50:   4.628 ms/op
                 existUser·p0.90:   5.898 ms/op
                 existUser·p0.95:   6.767 ms/op
                 existUser·p0.99:   9.142 ms/op
                 existUser·p0.999:  15.377 ms/op
                 existUser·p0.9999: 28.439 ms/op
                 existUser·p1.00:   28.869 ms/op

Iteration   2: 5.065 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.208 ms/op
                 existUser·p0.50:   4.686 ms/op
                 existUser·p0.90:   6.447 ms/op
                 existUser·p0.95:   7.782 ms/op
                 existUser·p0.99:   11.158 ms/op
                 existUser·p0.999:  23.658 ms/op
                 existUser·p0.9999: 31.414 ms/op
                 existUser·p1.00:   35.455 ms/op

Iteration   3: 4.813 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.253 ms/op
                 existUser·p0.50:   4.678 ms/op
                 existUser·p0.90:   5.472 ms/op
                 existUser·p0.95:   6.152 ms/op
                 existUser·p0.99:   9.019 ms/op
                 existUser·p0.999:  15.794 ms/op
                 existUser·p0.9999: 32.157 ms/op
                 existUser·p1.00:   33.817 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 194976
  mean =      4.917 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43 
    [ 2.500,  5.000) = 140308 
    [ 5.000,  7.500) = 47571 
    [ 7.500, 10.000) = 5020 
    [10.000, 12.500) = 1375 
    [12.500, 15.000) = 439 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 70 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.937 ms/op
     p(50.0000) =      4.669 ms/op
     p(90.0000) =      5.857 ms/op
     p(95.0000) =      6.939 ms/op
     p(99.0000) =     10.076 ms/op
     p(99.9000) =     16.601 ms/op
     p(99.9900) =     31.375 ms/op
     p(99.9990) =     33.899 ms/op
     p(99.9999) =     35.455 ms/op
    p(100.0000) =     35.455 ms/op


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
# Warmup Iteration   1: 16.778 ±(99.9%) 0.264 ms/op
# Warmup Iteration   2: 5.953 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.170 ±(99.9%) 0.019 ms/op
Iteration   1: 5.085 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.490 ms/op
                 getUser·p0.50:   4.866 ms/op
                 getUser·p0.90:   6.095 ms/op
                 getUser·p0.95:   7.021 ms/op
                 getUser·p0.99:   9.716 ms/op
                 getUser·p0.999:  22.336 ms/op
                 getUser·p0.9999: 25.844 ms/op
                 getUser·p1.00:   27.263 ms/op

Iteration   2: 5.315 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.153 ms/op
                 getUser·p0.50:   5.063 ms/op
                 getUser·p0.90:   6.242 ms/op
                 getUser·p0.95:   7.545 ms/op
                 getUser·p0.99:   10.633 ms/op
                 getUser·p0.999:  25.935 ms/op
                 getUser·p0.9999: 30.900 ms/op
                 getUser·p1.00:   32.375 ms/op

Iteration   3: 5.105 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.515 ms/op
                 getUser·p0.50:   4.874 ms/op
                 getUser·p0.90:   6.144 ms/op
                 getUser·p0.95:   6.889 ms/op
                 getUser·p0.99:   9.077 ms/op
                 getUser·p0.999:  27.214 ms/op
                 getUser·p0.9999: 33.529 ms/op
                 getUser·p1.00:   35.848 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 185687
  mean =      5.166 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 102294 
    [ 5.000,  7.500) = 76096 
    [ 7.500, 10.000) = 5621 
    [10.000, 12.500) = 1141 
    [12.500, 15.000) = 235 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.153 ms/op
     p(50.0000) =      4.932 ms/op
     p(90.0000) =      6.160 ms/op
     p(95.0000) =      7.078 ms/op
     p(99.0000) =      9.765 ms/op
     p(99.9000) =     22.653 ms/op
     p(99.9900) =     32.946 ms/op
     p(99.9990) =     34.388 ms/op
     p(99.9999) =     35.848 ms/op
    p(100.0000) =     35.848 ms/op


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
# Warmup Iteration   1: 18.673 ±(99.9%) 0.312 ms/op
# Warmup Iteration   2: 7.369 ±(99.9%) 0.051 ms/op
# Warmup Iteration   3: 6.188 ±(99.9%) 0.026 ms/op
Iteration   1: 6.028 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.286 ms/op
                 listUser·p0.50:   5.726 ms/op
                 listUser·p0.90:   7.070 ms/op
                 listUser·p0.95:   8.045 ms/op
                 listUser·p0.99:   11.272 ms/op
                 listUser·p0.999:  27.001 ms/op
                 listUser·p0.9999: 31.644 ms/op
                 listUser·p1.00:   33.620 ms/op

Iteration   2: 6.137 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.175 ms/op
                 listUser·p0.50:   5.915 ms/op
                 listUser·p0.90:   7.078 ms/op
                 listUser·p0.95:   7.922 ms/op
                 listUser·p0.99:   10.912 ms/op
                 listUser·p0.999:  27.677 ms/op
                 listUser·p0.9999: 31.509 ms/op
                 listUser·p1.00:   34.734 ms/op

Iteration   3: 6.191 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.769 ms/op
                 listUser·p0.50:   5.931 ms/op
                 listUser·p0.90:   7.070 ms/op
                 listUser·p0.95:   8.274 ms/op
                 listUser·p0.99:   11.780 ms/op
                 listUser·p0.999:  26.411 ms/op
                 listUser·p0.9999: 33.188 ms/op
                 listUser·p1.00:   34.341 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 156912
  mean =      6.118 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 9676 
    [ 5.000,  7.500) = 136352 
    [ 7.500, 10.000) = 7775 
    [10.000, 12.500) = 2193 
    [12.500, 15.000) = 480 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 124 
    [27.500, 30.000) = 96 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.175 ms/op
     p(50.0000) =      5.865 ms/op
     p(90.0000) =      7.070 ms/op
     p(95.0000) =      8.061 ms/op
     p(99.0000) =     11.338 ms/op
     p(99.9000) =     27.066 ms/op
     p(99.9900) =     31.621 ms/op
     p(99.9990) =     34.510 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.014 ± 4.703  ops/ms
ClientPb.existUser                       thrpt       3   6.577 ± 1.493  ops/ms
ClientPb.getUser                         thrpt       3   6.182 ± 2.019  ops/ms
ClientPb.listUser                        thrpt       3   5.140 ± 1.335  ops/ms
ClientPb.createUser                       avgt       3   5.087 ± 1.436   ms/op
ClientPb.existUser                        avgt       3   4.910 ± 2.717   ms/op
ClientPb.getUser                          avgt       3   5.127 ± 4.005   ms/op
ClientPb.listUser                         avgt       3   6.028 ± 1.054   ms/op
ClientPb.createUser                     sample  184729   5.194 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.245           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.940           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.324           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.152           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.634           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.299           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.606           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.996           ms/op
ClientPb.existUser                      sample  194976   4.917 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.937           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.669           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.857           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.939           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.076           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.601           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.375           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.455           ms/op
ClientPb.getUser                        sample  185687   5.166 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.153           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.932           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.160           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.078           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.765           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.653           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.946           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.848           ms/op
ClientPb.listUser                       sample  156912   6.118 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.175           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.865           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.070           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.061           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.338           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.066           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.621           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.734           ms/op
