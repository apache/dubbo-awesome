# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.647 ops/ms
# Warmup Iteration   2: 3.814 ops/ms
# Warmup Iteration   3: 7.388 ops/ms
Iteration   1: 7.381 ops/ms
Iteration   2: 7.953 ops/ms
Iteration   3: 8.026 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.787 ±(99.9%) 6.439 ops/ms [Average]
  (min, avg, max) = (7.381, 7.787, 8.026), stdev = 0.353
  CI (99.9%): [1.347, 14.226] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 2.332 ops/ms
# Warmup Iteration   2: 7.276 ops/ms
# Warmup Iteration   3: 8.474 ops/ms
Iteration   1: 8.337 ops/ms
Iteration   2: 8.342 ops/ms
Iteration   3: 8.011 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.230 ±(99.9%) 3.458 ops/ms [Average]
  (min, avg, max) = (8.011, 8.230, 8.342), stdev = 0.190
  CI (99.9%): [4.772, 11.689] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.157 ops/ms
# Warmup Iteration   2: 6.611 ops/ms
# Warmup Iteration   3: 7.642 ops/ms
Iteration   1: 8.060 ops/ms
Iteration   2: 7.798 ops/ms
Iteration   3: 8.055 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.971 ±(99.9%) 2.738 ops/ms [Average]
  (min, avg, max) = (7.798, 7.971, 8.060), stdev = 0.150
  CI (99.9%): [5.233, 10.709] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.103 ops/ms
# Warmup Iteration   2: 6.046 ops/ms
# Warmup Iteration   3: 6.780 ops/ms
Iteration   1: 6.735 ops/ms
Iteration   2: 6.889 ops/ms
Iteration   3: 6.598 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.741 ±(99.9%) 2.653 ops/ms [Average]
  (min, avg, max) = (6.598, 6.741, 6.889), stdev = 0.145
  CI (99.9%): [4.087, 9.394] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 14.077 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.601 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.096 ±(99.9%) 0.005 ms/op
Iteration   1: 3.948 ±(99.9%) 0.009 ms/op
Iteration   2: 4.064 ±(99.9%) 0.005 ms/op
Iteration   3: 3.764 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.925 ±(99.9%) 2.763 ms/op [Average]
  (min, avg, max) = (3.764, 3.925, 4.064), stdev = 0.151
  CI (99.9%): [1.162, 6.688] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 13.240 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.502 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.833 ±(99.9%) 0.009 ms/op
Iteration   1: 3.859 ±(99.9%) 0.008 ms/op
Iteration   2: 3.768 ±(99.9%) 0.004 ms/op
Iteration   3: 3.812 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.813 ±(99.9%) 0.827 ms/op [Average]
  (min, avg, max) = (3.768, 3.813, 3.859), stdev = 0.045
  CI (99.9%): [2.986, 4.640] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 12.257 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.659 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.022 ±(99.9%) 0.004 ms/op
Iteration   1: 3.876 ±(99.9%) 0.006 ms/op
Iteration   2: 3.833 ±(99.9%) 0.009 ms/op
Iteration   3: 3.914 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.874 ±(99.9%) 0.745 ms/op [Average]
  (min, avg, max) = (3.833, 3.874, 3.914), stdev = 0.041
  CI (99.9%): [3.130, 4.619] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 14.954 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 5.396 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.847 ±(99.9%) 0.009 ms/op
Iteration   1: 4.588 ±(99.9%) 0.013 ms/op
Iteration   2: 4.824 ±(99.9%) 0.007 ms/op
Iteration   3: 4.803 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.738 ±(99.9%) 2.381 ms/op [Average]
  (min, avg, max) = (4.588, 4.738, 4.824), stdev = 0.131
  CI (99.9%): [2.357, 7.120] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 13.592 ±(99.9%) 0.179 ms/op
# Warmup Iteration   2: 5.115 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.350 ±(99.9%) 0.018 ms/op
Iteration   1: 3.878 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.368 ms/op
                 createUser·p0.50:   3.707 ms/op
                 createUser·p0.90:   4.334 ms/op
                 createUser·p0.95:   4.653 ms/op
                 createUser·p0.99:   6.996 ms/op
                 createUser·p0.999:  24.330 ms/op
                 createUser·p0.9999: 36.766 ms/op
                 createUser·p1.00:   37.487 ms/op

Iteration   2: 3.954 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.800 ms/op
                 createUser·p0.50:   3.858 ms/op
                 createUser·p0.90:   4.375 ms/op
                 createUser·p0.95:   5.030 ms/op
                 createUser·p0.99:   6.873 ms/op
                 createUser·p0.999:  26.051 ms/op
                 createUser·p0.9999: 28.338 ms/op
                 createUser·p1.00:   29.000 ms/op

Iteration   3: 3.875 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.935 ms/op
                 createUser·p0.50:   3.830 ms/op
                 createUser·p0.90:   4.141 ms/op
                 createUser·p0.95:   4.612 ms/op
                 createUser·p0.99:   6.681 ms/op
                 createUser·p0.999:  13.594 ms/op
                 createUser·p0.9999: 32.809 ms/op
                 createUser·p1.00:   33.686 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 245983
  mean =      3.902 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 99 
    [ 2.500,  5.000) = 236542 
    [ 5.000,  7.500) = 7667 
    [ 7.500, 10.000) = 1138 
    [10.000, 12.500) = 208 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      1.368 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      6.849 ms/op
     p(99.9000) =     24.281 ms/op
     p(99.9900) =     35.979 ms/op
     p(99.9990) =     37.129 ms/op
     p(99.9999) =     37.487 ms/op
    p(100.0000) =     37.487 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 10.507 ±(99.9%) 0.171 ms/op
# Warmup Iteration   2: 4.234 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.908 ±(99.9%) 0.011 ms/op
Iteration   1: 4.038 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.165 ms/op
                 existUser·p0.50:   3.875 ms/op
                 existUser·p0.90:   4.628 ms/op
                 existUser·p0.95:   5.300 ms/op
                 existUser·p0.99:   7.463 ms/op
                 existUser·p0.999:  23.278 ms/op
                 existUser·p0.9999: 26.547 ms/op
                 existUser·p1.00:   27.165 ms/op

Iteration   2: 3.962 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.903 ms/op
                 existUser·p0.50:   3.768 ms/op
                 existUser·p0.90:   4.514 ms/op
                 existUser·p0.95:   5.333 ms/op
                 existUser·p0.99:   7.528 ms/op
                 existUser·p0.999:  16.048 ms/op
                 existUser·p0.9999: 29.819 ms/op
                 existUser·p1.00:   31.326 ms/op

Iteration   3: 3.856 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.688 ms/op
                 existUser·p0.50:   3.699 ms/op
                 existUser·p0.90:   4.202 ms/op
                 existUser·p0.95:   4.538 ms/op
                 existUser·p0.99:   7.512 ms/op
                 existUser·p0.999:  14.090 ms/op
                 existUser·p0.9999: 31.513 ms/op
                 existUser·p1.00:   32.866 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 242845
  mean =      3.951 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 206 
    [ 2.500,  5.000) = 228794 
    [ 5.000,  7.500) = 11441 
    [ 7.500, 10.000) = 1677 
    [10.000, 12.500) = 291 
    [12.500, 15.000) = 181 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 65 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.165 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      5.153 ms/op
     p(99.0000) =      7.487 ms/op
     p(99.9000) =     15.949 ms/op
     p(99.9900) =     30.015 ms/op
     p(99.9990) =     32.534 ms/op
     p(99.9999) =     32.866 ms/op
    p(100.0000) =     32.866 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.257 ±(99.9%) 0.205 ms/op
# Warmup Iteration   2: 4.749 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.087 ±(99.9%) 0.011 ms/op
Iteration   1: 4.171 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.372 ms/op
                 getUser·p0.50:   3.949 ms/op
                 getUser·p0.90:   4.956 ms/op
                 getUser·p0.95:   5.915 ms/op
                 getUser·p0.99:   8.094 ms/op
                 getUser·p0.999:  22.062 ms/op
                 getUser·p0.9999: 27.722 ms/op
                 getUser·p1.00:   28.049 ms/op

Iteration   2: 3.991 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.062 ms/op
                 getUser·p0.50:   3.854 ms/op
                 getUser·p0.90:   4.432 ms/op
                 getUser·p0.95:   4.833 ms/op
                 getUser·p0.99:   7.012 ms/op
                 getUser·p0.999:  24.895 ms/op
                 getUser·p0.9999: 30.080 ms/op
                 getUser·p1.00:   30.867 ms/op

Iteration   3: 4.107 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.827 ms/op
                 getUser·p0.50:   3.920 ms/op
                 getUser·p0.90:   4.858 ms/op
                 getUser·p0.95:   5.489 ms/op
                 getUser·p0.99:   7.356 ms/op
                 getUser·p0.999:  13.119 ms/op
                 getUser·p0.9999: 32.513 ms/op
                 getUser·p1.00:   34.210 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 234760
  mean =      4.088 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 97 
    [ 2.500,  5.000) = 217707 
    [ 5.000,  7.500) = 14478 
    [ 7.500, 10.000) = 1679 
    [10.000, 12.500) = 441 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 54 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.372 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      4.727 ms/op
     p(95.0000) =      5.415 ms/op
     p(99.0000) =      7.586 ms/op
     p(99.9000) =     22.167 ms/op
     p(99.9900) =     31.395 ms/op
     p(99.9990) =     33.896 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.278 ±(99.9%) 0.197 ms/op
# Warmup Iteration   2: 5.712 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.924 ±(99.9%) 0.017 ms/op
Iteration   1: 4.738 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.966 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.439 ms/op
                 listUser·p0.99:   8.897 ms/op
                 listUser·p0.999:  24.166 ms/op
                 listUser·p0.9999: 27.205 ms/op
                 listUser·p1.00:   28.475 ms/op

Iteration   2: 4.721 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.159 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.980 ms/op
                 listUser·p0.99:   8.356 ms/op
                 listUser·p0.999:  20.460 ms/op
                 listUser·p0.9999: 24.684 ms/op
                 listUser·p1.00:   27.296 ms/op

Iteration   3: 4.728 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.154 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   6.119 ms/op
                 listUser·p0.99:   8.815 ms/op
                 listUser·p0.999:  16.856 ms/op
                 listUser·p0.9999: 19.694 ms/op
                 listUser·p1.00:   19.694 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 202899
  mean =      4.729 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 173635 
    [ 5.000,  7.500) = 24596 
    [ 7.500, 10.000) = 3664 
    [10.000, 12.500) = 485 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      1.966 ms/op
     p(50.0000) =      4.563 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.898 ms/op
     p(99.0000) =      8.667 ms/op
     p(99.9000) =     20.090 ms/op
     p(99.9900) =     25.919 ms/op
     p(99.9990) =     28.335 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.787 ± 6.439  ops/ms
ClientPb.existUser                       thrpt       3   8.230 ± 3.458  ops/ms
ClientPb.getUser                         thrpt       3   7.971 ± 2.738  ops/ms
ClientPb.listUser                        thrpt       3   6.741 ± 2.653  ops/ms
ClientPb.createUser                       avgt       3   3.925 ± 2.763   ms/op
ClientPb.existUser                        avgt       3   3.813 ± 0.827   ms/op
ClientPb.getUser                          avgt       3   3.874 ± 0.745   ms/op
ClientPb.listUser                         avgt       3   4.738 ± 2.381   ms/op
ClientPb.createUser                     sample  245983   3.902 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.368           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.805           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.293           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.743           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.849           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.281           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.979           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.487           ms/op
ClientPb.existUser                      sample  242845   3.951 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.165           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.785           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.424           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.153           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.487           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.949           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.015           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.866           ms/op
ClientPb.getUser                        sample  234760   4.088 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.372           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.912           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.727           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.415           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.586           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.167           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.395           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.210           ms/op
ClientPb.listUser                       sample  202899   4.729 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.966           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.161           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.898           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.667           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.090           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.919           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.475           ms/op
