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
# Warmup Iteration   1: 1.536 ops/ms
# Warmup Iteration   2: 3.226 ops/ms
# Warmup Iteration   3: 6.620 ops/ms
Iteration   1: 7.278 ops/ms
Iteration   2: 7.410 ops/ms
Iteration   3: 7.383 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.357 ±(99.9%) 1.264 ops/ms [Average]
  (min, avg, max) = (7.278, 7.357, 7.410), stdev = 0.069
  CI (99.9%): [6.093, 8.620] (assumes normal distribution)


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
# Warmup Iteration   1: 2.173 ops/ms
# Warmup Iteration   2: 6.892 ops/ms
# Warmup Iteration   3: 8.047 ops/ms
Iteration   1: 8.149 ops/ms
Iteration   2: 7.503 ops/ms
Iteration   3: 7.962 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.871 ±(99.9%) 6.069 ops/ms [Average]
  (min, avg, max) = (7.503, 7.871, 8.149), stdev = 0.333
  CI (99.9%): [1.802, 13.941] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.105 ops/ms
# Warmup Iteration   2: 6.049 ops/ms
# Warmup Iteration   3: 7.559 ops/ms
Iteration   1: 7.541 ops/ms
Iteration   2: 7.821 ops/ms
Iteration   3: 7.819 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.727 ±(99.9%) 2.943 ops/ms [Average]
  (min, avg, max) = (7.541, 7.727, 7.821), stdev = 0.161
  CI (99.9%): [4.784, 10.670] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.807 ops/ms
# Warmup Iteration   2: 5.421 ops/ms
# Warmup Iteration   3: 6.402 ops/ms
Iteration   1: 6.505 ops/ms
Iteration   2: 6.382 ops/ms
Iteration   3: 6.802 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.563 ±(99.9%) 3.943 ops/ms [Average]
  (min, avg, max) = (6.382, 6.563, 6.802), stdev = 0.216
  CI (99.9%): [2.619, 10.506] (assumes normal distribution)


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
# Warmup Iteration   1: 11.870 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 5.383 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.484 ±(99.9%) 0.008 ms/op
Iteration   1: 4.249 ±(99.9%) 0.007 ms/op
Iteration   2: 4.233 ±(99.9%) 0.006 ms/op
Iteration   3: 4.275 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.252 ±(99.9%) 0.385 ms/op [Average]
  (min, avg, max) = (4.233, 4.252, 4.275), stdev = 0.021
  CI (99.9%): [3.867, 4.637] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 12.818 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.360 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.010 ±(99.9%) 0.005 ms/op
Iteration   1: 3.884 ±(99.9%) 0.010 ms/op
Iteration   2: 3.928 ±(99.9%) 0.008 ms/op
Iteration   3: 4.056 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.956 ±(99.9%) 1.622 ms/op [Average]
  (min, avg, max) = (3.884, 3.956, 4.056), stdev = 0.089
  CI (99.9%): [2.334, 5.579] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 13.501 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 5.095 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.562 ±(99.9%) 0.006 ms/op
Iteration   1: 4.279 ±(99.9%) 0.007 ms/op
Iteration   2: 4.244 ±(99.9%) 0.006 ms/op
Iteration   3: 4.038 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.187 ±(99.9%) 2.381 ms/op [Average]
  (min, avg, max) = (4.038, 4.187, 4.279), stdev = 0.130
  CI (99.9%): [1.806, 6.568] (assumes normal distribution)


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
# Warmup Iteration   1: 14.885 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 6.472 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.997 ±(99.9%) 0.010 ms/op
Iteration   1: 4.837 ±(99.9%) 0.013 ms/op
Iteration   2: 4.906 ±(99.9%) 0.010 ms/op
Iteration   3: 5.019 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.921 ±(99.9%) 1.680 ms/op [Average]
  (min, avg, max) = (4.837, 4.921, 5.019), stdev = 0.092
  CI (99.9%): [3.241, 6.600] (assumes normal distribution)


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
# Warmup Iteration   1: 14.547 ±(99.9%) 0.222 ms/op
# Warmup Iteration   2: 5.675 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 4.545 ±(99.9%) 0.018 ms/op
Iteration   1: 4.435 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.407 ms/op
                 createUser·p0.50:   4.116 ms/op
                 createUser·p0.90:   5.579 ms/op
                 createUser·p0.95:   6.988 ms/op
                 createUser·p0.99:   9.814 ms/op
                 createUser·p0.999:  14.500 ms/op
                 createUser·p0.9999: 27.596 ms/op
                 createUser·p1.00:   28.213 ms/op

Iteration   2: 4.117 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.126 ms/op
                 createUser·p0.50:   3.895 ms/op
                 createUser·p0.90:   4.653 ms/op
                 createUser·p0.95:   5.194 ms/op
                 createUser·p0.99:   8.069 ms/op
                 createUser·p0.999:  25.253 ms/op
                 createUser·p0.9999: 28.622 ms/op
                 createUser·p1.00:   29.557 ms/op

Iteration   3: 4.227 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   2.030 ms/op
                 createUser·p0.50:   4.067 ms/op
                 createUser·p0.90:   4.850 ms/op
                 createUser·p0.95:   5.390 ms/op
                 createUser·p0.99:   8.331 ms/op
                 createUser·p0.999:  14.308 ms/op
                 createUser·p0.9999: 36.166 ms/op
                 createUser·p1.00:   37.028 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 225527
  mean =      4.255 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 235 
    [ 2.500,  5.000) = 203805 
    [ 5.000,  7.500) = 16611 
    [ 7.500, 10.000) = 3542 
    [10.000, 12.500) = 901 
    [12.500, 15.000) = 192 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.126 ms/op
     p(50.0000) =      4.014 ms/op
     p(90.0000) =      4.964 ms/op
     p(95.0000) =      5.865 ms/op
     p(99.0000) =      8.962 ms/op
     p(99.9000) =     16.777 ms/op
     p(99.9900) =     35.376 ms/op
     p(99.9990) =     36.911 ms/op
     p(99.9999) =     37.028 ms/op
    p(100.0000) =     37.028 ms/op


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
# Warmup Iteration   1: 12.417 ±(99.9%) 0.206 ms/op
# Warmup Iteration   2: 4.663 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.278 ±(99.9%) 0.016 ms/op
Iteration   1: 4.097 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.870 ms/op
                 existUser·p0.50:   3.899 ms/op
                 existUser·p0.90:   4.768 ms/op
                 existUser·p0.95:   5.564 ms/op
                 existUser·p0.99:   8.135 ms/op
                 existUser·p0.999:  13.531 ms/op
                 existUser·p0.9999: 25.795 ms/op
                 existUser·p1.00:   26.444 ms/op

Iteration   2: 3.887 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.677 ms/op
                 existUser·p0.50:   3.748 ms/op
                 existUser·p0.90:   4.358 ms/op
                 existUser·p0.95:   4.727 ms/op
                 existUser·p0.99:   7.194 ms/op
                 existUser·p0.999:  12.312 ms/op
                 existUser·p0.9999: 32.793 ms/op
                 existUser·p1.00:   33.686 ms/op

Iteration   3: 3.925 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.534 ms/op
                 existUser·p0.50:   3.707 ms/op
                 existUser·p0.90:   4.293 ms/op
                 existUser·p0.95:   4.956 ms/op
                 existUser·p0.99:   8.585 ms/op
                 existUser·p0.999:  25.903 ms/op
                 existUser·p0.9999: 29.186 ms/op
                 existUser·p1.00:   31.162 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 241833
  mean =      3.967 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 300 
    [ 2.500,  5.000) = 229093 
    [ 5.000,  7.500) = 9031 
    [ 7.500, 10.000) = 2328 
    [10.000, 12.500) = 647 
    [12.500, 15.000) = 183 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 82 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.534 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      5.030 ms/op
     p(99.0000) =      8.167 ms/op
     p(99.9000) =     15.204 ms/op
     p(99.9900) =     32.139 ms/op
     p(99.9990) =     33.620 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


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
# Warmup Iteration   1: 13.557 ±(99.9%) 0.214 ms/op
# Warmup Iteration   2: 5.049 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.379 ±(99.9%) 0.016 ms/op
Iteration   1: 4.172 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.980 ms/op
                 getUser·p0.50:   3.908 ms/op
                 getUser·p0.90:   4.874 ms/op
                 getUser·p0.95:   5.939 ms/op
                 getUser·p0.99:   8.782 ms/op
                 getUser·p0.999:  24.740 ms/op
                 getUser·p0.9999: 27.033 ms/op
                 getUser·p1.00:   27.918 ms/op

Iteration   2: 4.090 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.191 ms/op
                 getUser·p0.50:   3.895 ms/op
                 getUser·p0.90:   4.571 ms/op
                 getUser·p0.95:   5.308 ms/op
                 getUser·p0.99:   8.438 ms/op
                 getUser·p0.999:  15.425 ms/op
                 getUser·p0.9999: 27.170 ms/op
                 getUser·p1.00:   28.344 ms/op

Iteration   3: 4.077 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.376 ms/op
                 getUser·p0.50:   3.916 ms/op
                 getUser·p0.90:   4.571 ms/op
                 getUser·p0.95:   4.940 ms/op
                 getUser·p0.99:   8.045 ms/op
                 getUser·p0.999:  13.495 ms/op
                 getUser·p0.9999: 31.982 ms/op
                 getUser·p1.00:   32.834 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 233418
  mean =      4.113 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33 
    [ 2.500,  5.000) = 218400 
    [ 5.000,  7.500) = 11074 
    [ 7.500, 10.000) = 2665 
    [10.000, 12.500) = 760 
    [12.500, 15.000) = 185 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 111 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 36 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.980 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      4.661 ms/op
     p(95.0000) =      5.325 ms/op
     p(99.0000) =      8.421 ms/op
     p(99.9000) =     16.597 ms/op
     p(99.9900) =     30.747 ms/op
     p(99.9990) =     32.582 ms/op
     p(99.9999) =     32.834 ms/op
    p(100.0000) =     32.834 ms/op


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
# Warmup Iteration   1: 15.494 ±(99.9%) 0.234 ms/op
# Warmup Iteration   2: 5.996 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.056 ±(99.9%) 0.021 ms/op
Iteration   1: 5.040 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.858 ms/op
                 listUser·p0.50:   4.735 ms/op
                 listUser·p0.90:   5.628 ms/op
                 listUser·p0.95:   7.082 ms/op
                 listUser·p0.99:   11.338 ms/op
                 listUser·p0.999:  27.886 ms/op
                 listUser·p0.9999: 31.282 ms/op
                 listUser·p1.00:   31.916 ms/op

Iteration   2: 4.999 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.495 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   5.825 ms/op
                 listUser·p0.95:   7.143 ms/op
                 listUser·p0.99:   10.018 ms/op
                 listUser·p0.999:  20.350 ms/op
                 listUser·p0.9999: 26.955 ms/op
                 listUser·p1.00:   27.722 ms/op

Iteration   3: 4.708 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.167 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.304 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   9.994 ms/op
                 listUser·p0.999:  16.941 ms/op
                 listUser·p0.9999: 19.405 ms/op
                 listUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 195368
  mean =      4.911 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 144427 
    [ 5.000,  7.500) = 43528 
    [ 7.500, 10.000) = 5010 
    [10.000, 12.500) = 1634 
    [12.500, 15.000) = 342 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.495 ms/op
     p(50.0000) =      4.571 ms/op
     p(90.0000) =      5.587 ms/op
     p(95.0000) =      6.619 ms/op
     p(99.0000) =     10.420 ms/op
     p(99.9000) =     20.202 ms/op
     p(99.9900) =     29.653 ms/op
     p(99.9990) =     31.635 ms/op
     p(99.9999) =     31.916 ms/op
    p(100.0000) =     31.916 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.357 ± 1.264  ops/ms
ClientPb.existUser                       thrpt       3   7.871 ± 6.069  ops/ms
ClientPb.getUser                         thrpt       3   7.727 ± 2.943  ops/ms
ClientPb.listUser                        thrpt       3   6.563 ± 3.943  ops/ms
ClientPb.createUser                       avgt       3   4.252 ± 0.385   ms/op
ClientPb.existUser                        avgt       3   3.956 ± 1.622   ms/op
ClientPb.getUser                          avgt       3   4.187 ± 2.381   ms/op
ClientPb.listUser                         avgt       3   4.921 ± 1.680   ms/op
ClientPb.createUser                     sample  225527   4.255 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.126           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.014           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.964           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.865           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.962           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.777           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.376           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.028           ms/op
ClientPb.existUser                      sample  241833   3.967 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.534           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.772           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.481           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.030           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.167           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.204           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.139           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.686           ms/op
ClientPb.getUser                        sample  233418   4.113 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.980           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.903           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.661           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.325           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.421           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.597           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.747           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.834           ms/op
ClientPb.listUser                       sample  195368   4.911 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.495           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.571           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.587           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.619           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.420           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.202           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.653           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.916           ms/op
