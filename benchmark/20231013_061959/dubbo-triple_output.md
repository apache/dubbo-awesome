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
# Warmup Iteration   1: 1.039 ops/ms
# Warmup Iteration   2: 2.830 ops/ms
# Warmup Iteration   3: 5.857 ops/ms
Iteration   1: 5.953 ops/ms
Iteration   2: 6.447 ops/ms
Iteration   3: 6.260 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.220 ±(99.9%) 4.555 ops/ms [Average]
  (min, avg, max) = (5.953, 6.220, 6.447), stdev = 0.250
  CI (99.9%): [1.664, 10.775] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.876 ops/ms
# Warmup Iteration   2: 6.062 ops/ms
# Warmup Iteration   3: 6.612 ops/ms
Iteration   1: 6.629 ops/ms
Iteration   2: 6.526 ops/ms
Iteration   3: 6.417 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.524 ±(99.9%) 1.935 ops/ms [Average]
  (min, avg, max) = (6.417, 6.524, 6.629), stdev = 0.106
  CI (99.9%): [4.589, 8.458] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.555 ops/ms
# Warmup Iteration   2: 5.153 ops/ms
# Warmup Iteration   3: 6.483 ops/ms
Iteration   1: 6.431 ops/ms
Iteration   2: 6.475 ops/ms
Iteration   3: 6.655 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.520 ±(99.9%) 2.160 ops/ms [Average]
  (min, avg, max) = (6.431, 6.520, 6.655), stdev = 0.118
  CI (99.9%): [4.360, 8.681] (assumes normal distribution)


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
# Warmup Iteration   1: 1.813 ops/ms
# Warmup Iteration   2: 4.834 ops/ms
# Warmup Iteration   3: 5.620 ops/ms
Iteration   1: 5.788 ops/ms
Iteration   2: 5.457 ops/ms
Iteration   3: 5.892 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.712 ±(99.9%) 4.137 ops/ms [Average]
  (min, avg, max) = (5.457, 5.712, 5.892), stdev = 0.227
  CI (99.9%): [1.575, 9.850] (assumes normal distribution)


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
# Warmup Iteration   1: 15.158 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 5.642 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.244 ±(99.9%) 0.008 ms/op
Iteration   1: 4.950 ±(99.9%) 0.008 ms/op
Iteration   2: 5.126 ±(99.9%) 0.010 ms/op
Iteration   3: 5.096 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.057 ±(99.9%) 1.717 ms/op [Average]
  (min, avg, max) = (4.950, 5.057, 5.126), stdev = 0.094
  CI (99.9%): [3.341, 6.774] (assumes normal distribution)


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
# Warmup Iteration   1: 15.891 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 5.194 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.622 ±(99.9%) 0.006 ms/op
Iteration   1: 4.807 ±(99.9%) 0.011 ms/op
Iteration   2: 4.907 ±(99.9%) 0.009 ms/op
Iteration   3: 4.934 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.883 ±(99.9%) 1.218 ms/op [Average]
  (min, avg, max) = (4.807, 4.883, 4.934), stdev = 0.067
  CI (99.9%): [3.664, 6.101] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 17.612 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 5.954 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.926 ±(99.9%) 0.016 ms/op
Iteration   1: 4.960 ±(99.9%) 0.010 ms/op
Iteration   2: 4.773 ±(99.9%) 0.008 ms/op
Iteration   3: 4.810 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.848 ±(99.9%) 1.810 ms/op [Average]
  (min, avg, max) = (4.773, 4.848, 4.960), stdev = 0.099
  CI (99.9%): [3.038, 6.657] (assumes normal distribution)


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
# Warmup Iteration   1: 16.448 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 6.338 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.651 ±(99.9%) 0.010 ms/op
Iteration   1: 5.676 ±(99.9%) 0.011 ms/op
Iteration   2: 5.479 ±(99.9%) 0.014 ms/op
Iteration   3: 5.419 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.524 ±(99.9%) 2.452 ms/op [Average]
  (min, avg, max) = (5.419, 5.524, 5.676), stdev = 0.134
  CI (99.9%): [3.072, 7.977] (assumes normal distribution)


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
# Warmup Iteration   1: 15.670 ±(99.9%) 0.248 ms/op
# Warmup Iteration   2: 5.828 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.177 ±(99.9%) 0.021 ms/op
Iteration   1: 4.626 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.108 ms/op
                 createUser·p0.50:   4.399 ms/op
                 createUser·p0.90:   5.538 ms/op
                 createUser·p0.95:   6.226 ms/op
                 createUser·p0.99:   8.749 ms/op
                 createUser·p0.999:  17.942 ms/op
                 createUser·p0.9999: 23.860 ms/op
                 createUser·p1.00:   24.740 ms/op

Iteration   2: 4.860 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.735 ms/op
                 createUser·p0.50:   4.628 ms/op
                 createUser·p0.90:   5.964 ms/op
                 createUser·p0.95:   6.668 ms/op
                 createUser·p0.99:   9.070 ms/op
                 createUser·p0.999:  21.501 ms/op
                 createUser·p0.9999: 26.014 ms/op
                 createUser·p1.00:   27.951 ms/op

Iteration   3: 4.918 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.841 ms/op
                 createUser·p0.50:   4.596 ms/op
                 createUser·p0.90:   6.029 ms/op
                 createUser·p0.95:   7.021 ms/op
                 createUser·p0.99:   10.140 ms/op
                 createUser·p0.999:  24.835 ms/op
                 createUser·p0.9999: 26.870 ms/op
                 createUser·p1.00:   28.082 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 200172
  mean =      4.798 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 110 
    [ 2.500,  5.000) = 145410 
    [ 5.000,  7.500) = 49003 
    [ 7.500, 10.000) = 4070 
    [10.000, 12.500) = 840 
    [12.500, 15.000) = 234 
    [15.000, 17.500) = 174 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 126 
    [25.000, 27.500) = 62 

  Percentiles, ms/op:
      p(0.0000) =      1.108 ms/op
     p(50.0000) =      4.530 ms/op
     p(90.0000) =      5.849 ms/op
     p(95.0000) =      6.660 ms/op
     p(99.0000) =      9.421 ms/op
     p(99.9000) =     22.260 ms/op
     p(99.9900) =     26.050 ms/op
     p(99.9990) =     28.049 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


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
# Warmup Iteration   1: 14.546 ±(99.9%) 0.199 ms/op
# Warmup Iteration   2: 5.177 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.622 ±(99.9%) 0.016 ms/op
Iteration   1: 4.717 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.626 ms/op
                 existUser·p0.50:   4.399 ms/op
                 existUser·p0.90:   6.095 ms/op
                 existUser·p0.95:   7.070 ms/op
                 existUser·p0.99:   9.224 ms/op
                 existUser·p0.999:  14.385 ms/op
                 existUser·p0.9999: 25.381 ms/op
                 existUser·p1.00:   26.247 ms/op

Iteration   2: 4.754 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.702 ms/op
                 existUser·p0.50:   4.415 ms/op
                 existUser·p0.90:   5.931 ms/op
                 existUser·p0.95:   6.971 ms/op
                 existUser·p0.99:   10.224 ms/op
                 existUser·p0.999:  18.603 ms/op
                 existUser·p0.9999: 28.536 ms/op
                 existUser·p1.00:   29.786 ms/op

Iteration   3: 4.600 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.032 ms/op
                 existUser·p0.50:   4.366 ms/op
                 existUser·p0.90:   5.497 ms/op
                 existUser·p0.95:   6.316 ms/op
                 existUser·p0.99:   8.897 ms/op
                 existUser·p0.999:  19.787 ms/op
                 existUser·p0.9999: 32.424 ms/op
                 existUser·p1.00:   36.700 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 204386
  mean =      4.689 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 104 
    [ 2.500,  5.000) = 157964 
    [ 5.000,  7.500) = 39585 
    [ 7.500, 10.000) = 5237 
    [10.000, 12.500) = 899 
    [12.500, 15.000) = 262 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 43 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.626 ms/op
     p(50.0000) =      4.391 ms/op
     p(90.0000) =      5.816 ms/op
     p(95.0000) =      6.832 ms/op
     p(99.0000) =      9.437 ms/op
     p(99.9000) =     18.337 ms/op
     p(99.9900) =     30.999 ms/op
     p(99.9990) =     36.546 ms/op
     p(99.9999) =     36.700 ms/op
    p(100.0000) =     36.700 ms/op


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
# Warmup Iteration   1: 13.820 ±(99.9%) 0.242 ms/op
# Warmup Iteration   2: 5.265 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.006 ±(99.9%) 0.018 ms/op
Iteration   1: 5.294 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.929 ms/op
                 getUser·p0.50:   4.891 ms/op
                 getUser·p0.90:   6.865 ms/op
                 getUser·p0.95:   8.126 ms/op
                 getUser·p0.99:   12.894 ms/op
                 getUser·p0.999:  18.448 ms/op
                 getUser·p0.9999: 26.637 ms/op
                 getUser·p1.00:   27.197 ms/op

Iteration   2: 5.077 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.200 ms/op
                 getUser·p0.50:   4.776 ms/op
                 getUser·p0.90:   6.021 ms/op
                 getUser·p0.95:   7.774 ms/op
                 getUser·p0.99:   10.997 ms/op
                 getUser·p0.999:  19.137 ms/op
                 getUser·p0.9999: 24.917 ms/op
                 getUser·p1.00:   25.690 ms/op

Iteration   3: 4.932 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.490 ms/op
                 getUser·p0.50:   4.686 ms/op
                 getUser·p0.90:   5.825 ms/op
                 getUser·p0.95:   6.955 ms/op
                 getUser·p0.99:   10.076 ms/op
                 getUser·p0.999:  22.251 ms/op
                 getUser·p0.9999: 24.642 ms/op
                 getUser·p1.00:   25.559 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 188273
  mean =      5.097 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 118308 
    [ 5.000,  7.500) = 59868 
    [ 7.500, 10.000) = 7063 
    [10.000, 12.500) = 1723 
    [12.500, 15.000) = 698 
    [15.000, 17.500) = 337 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.929 ms/op
     p(50.0000) =      4.776 ms/op
     p(90.0000) =      6.234 ms/op
     p(95.0000) =      7.643 ms/op
     p(99.0000) =     11.223 ms/op
     p(99.9000) =     19.390 ms/op
     p(99.9900) =     24.936 ms/op
     p(99.9990) =     26.937 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


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
# Warmup Iteration   1: 16.913 ±(99.9%) 0.282 ms/op
# Warmup Iteration   2: 6.703 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 6.247 ±(99.9%) 0.026 ms/op
Iteration   1: 5.985 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.735 ms/op
                 listUser·p0.50:   5.538 ms/op
                 listUser·p0.90:   7.371 ms/op
                 listUser·p0.95:   8.913 ms/op
                 listUser·p0.99:   12.485 ms/op
                 listUser·p0.999:  24.758 ms/op
                 listUser·p0.9999: 28.671 ms/op
                 listUser·p1.00:   29.360 ms/op

Iteration   2: 5.660 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.866 ms/op
                 listUser·p0.50:   5.341 ms/op
                 listUser·p0.90:   6.611 ms/op
                 listUser·p0.95:   7.938 ms/op
                 listUser·p0.99:   11.272 ms/op
                 listUser·p0.999:  24.379 ms/op
                 listUser·p0.9999: 27.492 ms/op
                 listUser·p1.00:   29.229 ms/op

Iteration   3: 5.636 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.985 ms/op
                 listUser·p0.50:   5.333 ms/op
                 listUser·p0.90:   6.627 ms/op
                 listUser·p0.95:   8.184 ms/op
                 listUser·p0.99:   11.338 ms/op
                 listUser·p0.999:  19.497 ms/op
                 listUser·p0.9999: 23.199 ms/op
                 listUser·p1.00:   27.656 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 166767
  mean =      5.756 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 40808 
    [ 5.000,  7.500) = 113943 
    [ 7.500, 10.000) = 8394 
    [10.000, 12.500) = 2337 
    [12.500, 15.000) = 521 
    [15.000, 17.500) = 285 
    [17.500, 20.000) = 146 
    [20.000, 22.500) = 122 
    [22.500, 25.000) = 101 
    [25.000, 27.500) = 73 

  Percentiles, ms/op:
      p(0.0000) =      1.735 ms/op
     p(50.0000) =      5.407 ms/op
     p(90.0000) =      6.889 ms/op
     p(95.0000) =      8.380 ms/op
     p(99.0000) =     11.911 ms/op
     p(99.9000) =     23.207 ms/op
     p(99.9900) =     27.623 ms/op
     p(99.9990) =     29.360 ms/op
     p(99.9999) =     29.360 ms/op
    p(100.0000) =     29.360 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.220 ± 4.555  ops/ms
ClientPb.existUser                       thrpt       3   6.524 ± 1.935  ops/ms
ClientPb.getUser                         thrpt       3   6.520 ± 2.160  ops/ms
ClientPb.listUser                        thrpt       3   5.712 ± 4.137  ops/ms
ClientPb.createUser                       avgt       3   5.057 ± 1.717   ms/op
ClientPb.existUser                        avgt       3   4.883 ± 1.218   ms/op
ClientPb.getUser                          avgt       3   4.848 ± 1.810   ms/op
ClientPb.listUser                         avgt       3   5.524 ± 2.452   ms/op
ClientPb.createUser                     sample  200172   4.798 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.108           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.530           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.849           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.660           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.421           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.260           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.050           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.082           ms/op
ClientPb.existUser                      sample  204386   4.689 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.626           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.391           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.816           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.832           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.437           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.337           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.999           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.700           ms/op
ClientPb.getUser                        sample  188273   5.097 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.929           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.776           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.234           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.643           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.223           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.390           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.936           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.197           ms/op
ClientPb.listUser                       sample  166767   5.756 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.735           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.407           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.889           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.380           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.911           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.207           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.623           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.360           ms/op
