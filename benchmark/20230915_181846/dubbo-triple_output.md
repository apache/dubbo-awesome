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
# Warmup Iteration   1: 1.218 ops/ms
# Warmup Iteration   2: 2.860 ops/ms
# Warmup Iteration   3: 5.570 ops/ms
Iteration   1: 5.973 ops/ms
Iteration   2: 6.106 ops/ms
Iteration   3: 6.250 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.110 ±(99.9%) 2.526 ops/ms [Average]
  (min, avg, max) = (5.973, 6.110, 6.250), stdev = 0.138
  CI (99.9%): [3.584, 8.636] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 1.970 ops/ms
# Warmup Iteration   2: 5.480 ops/ms
# Warmup Iteration   3: 6.414 ops/ms
Iteration   1: 6.754 ops/ms
Iteration   2: 6.450 ops/ms
Iteration   3: 6.310 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.505 ±(99.9%) 4.134 ops/ms [Average]
  (min, avg, max) = (6.310, 6.505, 6.754), stdev = 0.227
  CI (99.9%): [2.370, 10.639] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.746 ops/ms
# Warmup Iteration   2: 5.052 ops/ms
# Warmup Iteration   3: 5.940 ops/ms
Iteration   1: 5.912 ops/ms
Iteration   2: 6.376 ops/ms
Iteration   3: 6.108 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.132 ±(99.9%) 4.245 ops/ms [Average]
  (min, avg, max) = (5.912, 6.132, 6.376), stdev = 0.233
  CI (99.9%): [1.886, 10.377] (assumes normal distribution)


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
# Warmup Iteration   1: 1.601 ops/ms
# Warmup Iteration   2: 4.367 ops/ms
# Warmup Iteration   3: 5.166 ops/ms
Iteration   1: 5.269 ops/ms
Iteration   2: 5.069 ops/ms
Iteration   3: 5.181 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.173 ±(99.9%) 1.830 ops/ms [Average]
  (min, avg, max) = (5.069, 5.173, 5.269), stdev = 0.100
  CI (99.9%): [3.343, 7.003] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 18.952 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 6.166 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.261 ±(99.9%) 0.011 ms/op
Iteration   1: 5.222 ±(99.9%) 0.008 ms/op
Iteration   2: 5.184 ±(99.9%) 0.010 ms/op
Iteration   3: 5.137 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.181 ±(99.9%) 0.775 ms/op [Average]
  (min, avg, max) = (5.137, 5.181, 5.222), stdev = 0.042
  CI (99.9%): [4.406, 5.956] (assumes normal distribution)


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
# Warmup Iteration   1: 15.775 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 6.156 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 5.038 ±(99.9%) 0.006 ms/op
Iteration   1: 5.015 ±(99.9%) 0.007 ms/op
Iteration   2: 5.030 ±(99.9%) 0.006 ms/op
Iteration   3: 5.076 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.040 ±(99.9%) 0.574 ms/op [Average]
  (min, avg, max) = (5.015, 5.040, 5.076), stdev = 0.031
  CI (99.9%): [4.467, 5.614] (assumes normal distribution)


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
# Warmup Iteration   1: 16.135 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 6.150 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.445 ±(99.9%) 0.007 ms/op
Iteration   1: 5.382 ±(99.9%) 0.007 ms/op
Iteration   2: 5.258 ±(99.9%) 0.006 ms/op
Iteration   3: 5.403 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.348 ±(99.9%) 1.427 ms/op [Average]
  (min, avg, max) = (5.258, 5.348, 5.403), stdev = 0.078
  CI (99.9%): [3.921, 6.774] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 20.214 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 6.956 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 6.297 ±(99.9%) 0.009 ms/op
Iteration   1: 6.166 ±(99.9%) 0.011 ms/op
Iteration   2: 6.230 ±(99.9%) 0.010 ms/op
Iteration   3: 6.321 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.239 ±(99.9%) 1.424 ms/op [Average]
  (min, avg, max) = (6.166, 6.239, 6.321), stdev = 0.078
  CI (99.9%): [4.815, 7.663] (assumes normal distribution)


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
# Warmup Iteration   1: 17.141 ±(99.9%) 0.251 ms/op
# Warmup Iteration   2: 6.672 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.559 ±(99.9%) 0.023 ms/op
Iteration   1: 5.517 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.673 ms/op
                 createUser·p0.50:   5.202 ms/op
                 createUser·p0.90:   6.791 ms/op
                 createUser·p0.95:   7.684 ms/op
                 createUser·p0.99:   10.748 ms/op
                 createUser·p0.999:  23.987 ms/op
                 createUser·p0.9999: 28.961 ms/op
                 createUser·p1.00:   29.753 ms/op

Iteration   2: 5.106 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.722 ms/op
                 createUser·p0.50:   4.866 ms/op
                 createUser·p0.90:   6.054 ms/op
                 createUser·p0.95:   6.685 ms/op
                 createUser·p0.99:   9.322 ms/op
                 createUser·p0.999:  28.422 ms/op
                 createUser·p0.9999: 32.770 ms/op
                 createUser·p1.00:   33.456 ms/op

Iteration   3: 5.245 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.367 ms/op
                 createUser·p0.50:   5.046 ms/op
                 createUser·p0.90:   6.259 ms/op
                 createUser·p0.95:   6.857 ms/op
                 createUser·p0.99:   9.126 ms/op
                 createUser·p0.999:  24.977 ms/op
                 createUser·p0.9999: 29.316 ms/op
                 createUser·p1.00:   29.721 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 181470
  mean =      5.284 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 89012 
    [ 5.000,  7.500) = 85633 
    [ 7.500, 10.000) = 5034 
    [10.000, 12.500) = 1000 
    [12.500, 15.000) = 344 
    [15.000, 17.500) = 154 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 74 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.673 ms/op
     p(50.0000) =      5.022 ms/op
     p(90.0000) =      6.390 ms/op
     p(95.0000) =      7.102 ms/op
     p(99.0000) =      9.929 ms/op
     p(99.9000) =     24.674 ms/op
     p(99.9900) =     31.340 ms/op
     p(99.9990) =     33.349 ms/op
     p(99.9999) =     33.456 ms/op
    p(100.0000) =     33.456 ms/op


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
# Warmup Iteration   1: 15.777 ±(99.9%) 0.238 ms/op
# Warmup Iteration   2: 5.825 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.223 ±(99.9%) 0.021 ms/op
Iteration   1: 4.990 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.839 ms/op
                 existUser·p0.50:   4.776 ms/op
                 existUser·p0.90:   5.898 ms/op
                 existUser·p0.95:   6.701 ms/op
                 existUser·p0.99:   9.748 ms/op
                 existUser·p0.999:  22.792 ms/op
                 existUser·p0.9999: 27.269 ms/op
                 existUser·p1.00:   27.460 ms/op

Iteration   2: 4.911 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.179 ms/op
                 existUser·p0.50:   4.710 ms/op
                 existUser·p0.90:   5.825 ms/op
                 existUser·p0.95:   6.365 ms/op
                 existUser·p0.99:   8.684 ms/op
                 existUser·p0.999:  13.173 ms/op
                 existUser·p0.9999: 31.916 ms/op
                 existUser·p1.00:   32.145 ms/op

Iteration   3: 4.941 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.306 ms/op
                 existUser·p0.50:   4.719 ms/op
                 existUser·p0.90:   5.841 ms/op
                 existUser·p0.95:   6.586 ms/op
                 existUser·p0.99:   10.109 ms/op
                 existUser·p0.999:  16.810 ms/op
                 existUser·p0.9999: 28.801 ms/op
                 existUser·p1.00:   30.441 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 193859
  mean =      4.947 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45 
    [ 2.500,  5.000) = 131134 
    [ 5.000,  7.500) = 57650 
    [ 7.500, 10.000) = 3522 
    [10.000, 12.500) = 929 
    [12.500, 15.000) = 251 
    [15.000, 17.500) = 145 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 76 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.839 ms/op
     p(50.0000) =      4.735 ms/op
     p(90.0000) =      5.857 ms/op
     p(95.0000) =      6.529 ms/op
     p(99.0000) =      9.372 ms/op
     p(99.9000) =     16.810 ms/op
     p(99.9900) =     30.842 ms/op
     p(99.9990) =     31.992 ms/op
     p(99.9999) =     32.145 ms/op
    p(100.0000) =     32.145 ms/op


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
# Warmup Iteration   1: 16.636 ±(99.9%) 0.249 ms/op
# Warmup Iteration   2: 6.339 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.400 ±(99.9%) 0.019 ms/op
Iteration   1: 5.236 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.976 ms/op
                 getUser·p0.50:   5.038 ms/op
                 getUser·p0.90:   6.070 ms/op
                 getUser·p0.95:   6.750 ms/op
                 getUser·p0.99:   10.043 ms/op
                 getUser·p0.999:  20.955 ms/op
                 getUser·p0.9999: 24.179 ms/op
                 getUser·p1.00:   24.805 ms/op

Iteration   2: 5.383 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.179 ms/op
                 getUser·p0.50:   5.079 ms/op
                 getUser·p0.90:   6.540 ms/op
                 getUser·p0.95:   7.905 ms/op
                 getUser·p0.99:   11.682 ms/op
                 getUser·p0.999:  23.603 ms/op
                 getUser·p0.9999: 26.509 ms/op
                 getUser·p1.00:   28.639 ms/op

Iteration   3: 5.258 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.853 ms/op
                 getUser·p0.50:   4.973 ms/op
                 getUser·p0.90:   6.316 ms/op
                 getUser·p0.95:   7.553 ms/op
                 getUser·p0.99:   10.355 ms/op
                 getUser·p0.999:  23.822 ms/op
                 getUser·p0.9999: 27.159 ms/op
                 getUser·p1.00:   29.393 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 181405
  mean =      5.292 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 87845 
    [ 5.000,  7.500) = 85025 
    [ 7.500, 10.000) = 5918 
    [10.000, 12.500) = 1608 
    [12.500, 15.000) = 672 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 85 

  Percentiles, ms/op:
      p(0.0000) =      1.853 ms/op
     p(50.0000) =      5.030 ms/op
     p(90.0000) =      6.308 ms/op
     p(95.0000) =      7.365 ms/op
     p(99.0000) =     10.912 ms/op
     p(99.9000) =     21.547 ms/op
     p(99.9900) =     26.771 ms/op
     p(99.9990) =     28.779 ms/op
     p(99.9999) =     29.393 ms/op
    p(100.0000) =     29.393 ms/op


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
# Warmup Iteration   1: 18.167 ±(99.9%) 0.313 ms/op
# Warmup Iteration   2: 7.034 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 6.224 ±(99.9%) 0.024 ms/op
Iteration   1: 6.097 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.306 ms/op
                 listUser·p0.50:   5.784 ms/op
                 listUser·p0.90:   7.225 ms/op
                 listUser·p0.95:   8.293 ms/op
                 listUser·p0.99:   11.549 ms/op
                 listUser·p0.999:  24.149 ms/op
                 listUser·p0.9999: 27.221 ms/op
                 listUser·p1.00:   29.065 ms/op

Iteration   2: 6.143 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.786 ms/op
                 listUser·p0.50:   5.906 ms/op
                 listUser·p0.90:   7.143 ms/op
                 listUser·p0.95:   8.053 ms/op
                 listUser·p0.99:   11.321 ms/op
                 listUser·p0.999:  25.553 ms/op
                 listUser·p0.9999: 28.403 ms/op
                 listUser·p1.00:   28.836 ms/op

Iteration   3: 6.326 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.702 ms/op
                 listUser·p0.50:   6.046 ms/op
                 listUser·p0.90:   7.463 ms/op
                 listUser·p0.95:   8.716 ms/op
                 listUser·p0.99:   11.534 ms/op
                 listUser·p0.999:  20.836 ms/op
                 listUser·p0.9999: 24.266 ms/op
                 listUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 155143
  mean =      6.187 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 9741 
    [ 5.000,  7.500) = 132364 
    [ 7.500, 10.000) = 9664 
    [10.000, 12.500) = 2417 
    [12.500, 15.000) = 515 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 88 

  Percentiles, ms/op:
      p(0.0000) =      1.702 ms/op
     p(50.0000) =      5.915 ms/op
     p(90.0000) =      7.274 ms/op
     p(95.0000) =      8.348 ms/op
     p(99.0000) =     11.485 ms/op
     p(99.9000) =     24.014 ms/op
     p(99.9900) =     27.750 ms/op
     p(99.9990) =     29.029 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.110 ± 2.526  ops/ms
ClientPb.existUser                       thrpt       3   6.505 ± 4.134  ops/ms
ClientPb.getUser                         thrpt       3   6.132 ± 4.245  ops/ms
ClientPb.listUser                        thrpt       3   5.173 ± 1.830  ops/ms
ClientPb.createUser                       avgt       3   5.181 ± 0.775   ms/op
ClientPb.existUser                        avgt       3   5.040 ± 0.574   ms/op
ClientPb.getUser                          avgt       3   5.348 ± 1.427   ms/op
ClientPb.listUser                         avgt       3   6.239 ± 1.424   ms/op
ClientPb.createUser                     sample  181470   5.284 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.673           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.022           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.390           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.102           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.929           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.674           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.340           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.456           ms/op
ClientPb.existUser                      sample  193859   4.947 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.839           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.735           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.857           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.529           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.372           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.810           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.842           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.145           ms/op
ClientPb.getUser                        sample  181405   5.292 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.853           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.030           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.308           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.365           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.912           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.547           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.771           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.393           ms/op
ClientPb.listUser                       sample  155143   6.187 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.702           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.915           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.274           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.348           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.485           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.014           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.750           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.065           ms/op
